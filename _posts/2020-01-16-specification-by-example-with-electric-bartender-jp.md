---
title: "実例による仕様 Cucumber/Java Specification By Example (SBE) 電子バーテンダー"
---

プロダクトバックログリファインメントを行なっている間は、ユーザーストーリーではなく、実例による仕様（Specification By Example、以降SBE）を用いることをお勧めします。ビジネス側の人と開発者は、ホワイトボードを使用して共同作業します。 Cucumberを使用すると、非技術者であっても [Feature Files](#feature-fileの例)
は理解できるはずです。

開発チームは、スプリントの実行中に [Step Definitions](#step-definitionsの例) を作成します。

実例による仕様（SBE）の東京ワークショップでは、下記の電子バーテンダーの例を用いて進められます。この電子バーテンダーの例を作成するにあたり、[金井
大輝](https://www.odd-e.jp/team_06/) 氏と Emerson Mills
にご助力いただきました。実例による仕様（SBE）は Gojko Adžić によって提唱・展開されました。

実例による仕様（SBE）の詳細については、お問い合わせください。

## Feature Fileの例

~~~ Gherkin
Feature: 電子バーテンダーはビールの操作を可能である
#Feature: Electric bartender can work the beer kegs
  Background:
    Given 私達のバーでは50リットルの樽を使う
    And 300MLのビールグラスを使う

  Scenario: ゲストはエールを飲みたがっている
    Given バーにエールが満タンの樽がある
    When ゲストがエールををオーダーする
    Then ゲストのビールグラスにエールが満タンになる

  Scenario Outline: バーはエールの在庫を減らす為に管理する
    Given バーにエールが満タンの樽がある
    When お客様が <数> 杯のエールを注文する
    Then 樽には <残り> リットルが残っている
    Examples:
      | 数 | 残り   |
      | 1 | 49.7 |
      | 3 | 49.1 |

~~~

## Step Definitionsの例
~~~ Java
package cucumber.stepdefs;

import com.odde.electricbartender.AleKeg;
import com.odde.electricbartender.Bar;
import com.odde.electricbartender.BeerGlass;
import cucumber.api.java.en.Given;
import cucumber.api.java.en.Then;
import cucumber.api.java.en.When;

import static org.junit.Assert.assertEquals;
import static org.junit.Assert.assertNotEquals;


public class StepDefs {
    private Bar bar = new Bar();
    private BeerGlass beerGlass = new BeerGlass();

    @Given("私達のバーでは{int}リットルの樽を使う")  // @Given("Our bar uses {int} liter kegs")
    public void our_bar_uses_x_liter_kegs(int x) {
        int expectedKegCapacityInMilliliters = x * 1000;
        AleKeg keg = bar.getAleKeg();
        assertEquals(expectedKegCapacityInMilliliters, keg.totalCapacityInMilliliters());
    }

    @Given("バーにエールが満タンの樽がある") //@Given("the bar has a full keg of ale")
    public void バーにエールが満タンの樽がある() {
        bar.restockAle();
    }

    @Given("{int}MLのビールグラスを使う")  // @Given("Our bar uses {int}ml beer glasses")
    public void our_bar_uses_x_ml_beer_glasses(int x) {
        assertEquals(x, beerGlass.getTotalCapacityInMilliters());
    }

    @When("お客様が {int} 杯のエールを注文する")
    public void guest_orders_x_glasses_of_ale(int x) {
        for (int ii = 0; ii < x; ii++) {
            guest_orders_an_ale();
        }
    }

    @When("ゲストがエールををオーダーする")
    public void guest_orders_an_ale() {
        beerGlass = bar.takeAGlassOfBeer();
    }

    @Then("ゲストのビールグラスにエールが満タンになる")
    public void ゲストのビールグラスにエールが満タンになる() {
        assertNotEquals(0, beerGlass.getRemainingBeerInMilliliters());
    }

    @Then("樽には {double} リットルが残っている")
    public void 樽には_リットルが残っている(Double x) {
        int expectedBeerRemainingInMilliliters = (int) (x * 1000);
        AleKeg keg = bar.getAleKeg();
        assertEquals(expectedBeerRemainingInMilliliters, keg.remainingBeerInMilliliters());
    }
}
~~~
