---
title: '局所最適化バイアス：今ここで　対　後にどこかで'
header:
   og_image: /images/team-productivity-local-optimization-bias.png
   teaser: /images/team-productivity-local-optimization-bias.png
excerpt: 'ソフトウェア開発について深く理解していない人は、大規模なアジリティは複数の「超生産的」なチームの作業の総計だと考えるかもしれません。一見、論理的に思えるかもしれません。馬の足が早ければ早いほど、馬車も速く進むと考えませんか？しかし、賢明な読者のみなさんは、ソフトウェア開発は馬車を引っ張る馬とはわけが違うことは理解しているはずです。'
---
{::comment}title:  Local Optimization Bias: Here and Now vs. Elsewhere and Later
{:/comment}

{::comment}
We human animals naturally think about what’s right in front of us.  We focus on the here and now.  This served us well enough when life was simpler.  But actions also have effects we don't usually consider very well, either due to time -- because they happen later on -- , or distance -- they affect people or things we don't often interact with.

I’ve heard this blind spot called local optimization bias.  
{:/comment}

私たち人間という動物は、自然と目先のことを優先的に考えます。今この場で起きていることに囚われてしまいがちです。人の生活がまだ単純だったころは、これでよかったでしょう。ただし、私たちがとる行動は、ときに普段あまり考えていないような結果を伴います。これは、時間（時間が経過した後に発生する場合）、あるいは距離（離れた場所で発生する場合）によるものです。つまり、私たちがとる行動が、思わぬときに思わぬところで、あまり関わりのない人やものごとに影響を及ぼすこということです。

この盲点は、局所最適化バイアスと呼ばれることがあります。

{::comment}
## Example 1

The following video illustrates local optimization in a typical organization.  A supervisor instructs workers to prevent any unwrapped chocolate from getting past them into the next room.  They mostly succeed.  But in the long run and in the big picture, optimizing locally harms the business, its employees, and its customers.  The video is supposed to be funny, but I want you to take it seriously because similar things happen every day in your own company.
{:/comment}

## 例1

次の動画では、典型的な組織での局所最適化が見られます。管理者は、包装されていないチョコレートが隣のラインに混入しないように従業員に指示します。ほぼ問題なくできています。しかし長期的に、且つ全体的に見たら、局所的な最適化はビジネス・従業員・顧客全体に被害を及ぼしてしまいます。これは滑稽な動画のはずですが、あなたの会社では毎日のように似たようなことが起こっているので、真剣に受け止めてください。

{% include video id="HnbNcQlzV-4?rel=0" provider="youtube" %}

{::comment}
In the video above, *all three employees are acting correctly*!  It's easy to demonize the line manager, but she is doing exactly what she should be doing for her role in the organization, given the current structure and policies.  
{:/comment}

上の動画では、 3人の従業員全員が正しく行動しています！ ラインマネージャーを悪者にするのは簡単ですが、動画内で設定されている組織の構造と方針を考慮すると、彼女は組織での自分の役割を正確に果たしています。

### アクションなしのトレーニングは「チェンジ・シアター」を生み出しますか？

{::comment}
Just sending them to Scrum or LeSS training without changing the organizational design will not make a difference other than renaming the roles to Agile-sounding labels, inoculating the organization from fundamental change.  Without changes to organizational design, it's also futile to send the line manager to [leadership training](https://www.amazon.com/Leadership-BS-Fixing-Workplaces-Careers/dp/0062383167) or lecturing her to change her mindset and behavior.  Why should she?  As Craig Larman would say (paraphrasing [Larman's Laws](https://www.craiglarman.com/wiki/index.php?title=Larman%27s_Laws_of_Organizational_Behavior)),
{:/comment}


組織設計を変更せずに、従業員をスクラムやLeSSのトレーニングに送り込むと、ただ役割の名称をアジャイルらしく変更する結果に終わるだけでなく、根本的な組織の変化を阻むことになってしまいます。 組織設計を変更せずに、ラインマネージャーを[リーダーシップトレーニング](https://www.amazon.com/Leadership-BS-Fixing-Workplaces-Careers/dp/0062383167)に派遣したり、そのラインマネージャーに考え方や行動を変えるように説くことも無駄です。組織設計は従来のままなのに、考え方や行動を新たにする必要があるでしょうか？Craig Larmanが言うように（[Larman's Laws](/larmans-laws-jp)より、わかりやすく書き換えてあります）、


> 文化は構造に従います。確立された大規模なグループでは、文化や行動や考え方は、組織の体制や設計に従い、そして影響されます。すなわち、確立された大規模な組織で、実際に文化を変えたければ、まずは組織の体制から変えなければなりません（グループ、チーム、役割と責任、階層、昇進、方針、査定と報酬の仕組みなど）。そうでなければ、本当の意味で文化は変わらないでしょう。
>
> 別の言い方をすると、組織の体制は考え方や行動に強く影響します。
>
> Culture follows structure.  In big established groups, culture/behavior/mindset follows and is influenced by changes in the organizational system and design. That is, in large established organizations, if you want to really change culture, you have to start with changing the organizational system (groups, teams, roles and responsibilities, hierarchies, career paths, policies, measurement and reward mechanisms, etc), because culture does not really change otherwise.
>
> Said another way, the organizational system is strongly influential on mindset and behavior.

## 例2
{::comment}
During the 1980’s I had a brief stint in an IT department. Our IT department was actually called Information Services & Control (IS&C). One of my responsibilities was to prevent engineering teams from buying the tools they wanted to use because we could bulk purchase slightly cheaper alternatives that were “almost as good,” or to force people to use our unwieldy Univac mainframe. This is a reasonable argument that could be right in some cases.
{:/comment}

1980年代に、私はしばらくの間IT部門に配属されたことがあります。当時の会社のIT部門は、Information Services&Control (IS&C) と呼ばれていました。IS&C在籍中の私の仕事には、エンジニアリングチームが使用したいツールを購入できないようにするということが含まれていました。というのは、IS&Cは「ほぼ同じ」機能を持つわずかに安い代替品を大量購入することにより経費を節約できる、そして扱いにくいUnivacメインフレームの使用を強制させることにより、全てのデータをコントロールできると考えたからです。こうしたやり方は合理的で、場合によっては正しいこともあります。

{::comment}My boss produced reports for his boss showing how much money we’d saved the company. Those people probably all retired thinking this was the right thing to do. But today I realize what I did to save pennies was actually harmful in the big picture. Penny wise, pound foolish is an example of local optimization bias.{:/comment}

私の上司は、彼自身の上司に対して自分たちがどれだけ会社の経費を節約したのかを示すレポートを作成しました。この上司のような人々は、自分たちは正しいことをやっていると思いながら定年退職したでしょう。しかし、経費をごくわずかに節約するという私の過去の行いが、長期的にはかえって害をなしていたいうことを、私は今になって悟りました。「安物買いの銭失い」は、局所最適化バイアスの一例です。

{::comment}
> People who only look at the numbers are the worst of all.

-- Taiichi Ohno
{:/comment}

> 数字の読めないやつは話にならない。数字が見えない現場もいかん。だけどな、数字しか見ないやつが一番いかん。

--大野耐一

{::comment}## Example 3{:/comment}

## 例3

[![チームの生産性 局所最適化バイアス](../images/team-productivity-local-optimization-bias.png){: .align-center width="340"}](/why-scrum-isnt-making-your-company-very-agile)


{::comment}Beginning Scrum Masters –– including some book authors –– focus on trying to make "hyperproductive" teams instead of helping the product development organization become better able to learn and adapt.{:/comment}

初心者のスクラムマスター（本の著者を含む）は、製品開発組織の教育を改善したり、チームの適応力向上を支援したりするのではなく、単に超生産的(hyperproductive)なチームを作ることに躍起になっています。

{::comment}A person without a deep understanding of software development might assume that large scale agility comes from summing the work of multiple "hyperproductive" teams.  It seems logical at first glance.  Shouldn't faster horses pull the wagon faster?  But you, gentle and wise reader, know that software development is not like horses pulling a wagon.  In the big picture, everyone trying to be hyperproductive will produce a God-awful mess, not a faster company.  We will not out-learn our competition this way.  A locally-optimizing Scrum Master is the enemy of large scale agility.  {:/comment}

ソフトウェア開発について深く理解していない人は、大規模なアジリティは複数の「超生産的」なチームの作業の総計だと考えるかもしれません。一見、論理的に思えるかもしれません。馬の足が早ければ早いほど、馬車も速く進むと考えませんか？しかし、賢明な読者のみなさんは、ソフトウェア開発は馬車を引っ張る馬とはわけが違うことは理解しているはずです。全体像を見ると、超生産性を目指そうとする人はだれもかれも、より速い会社ではなく、とてつもない混乱を創り上げるだけです。これでは競合他社に勝つことはできません。局所的な最適化しか行わないスクラムマスターは、まさに大規模なアジリティの大敵です。

{::comment}Do you have some examples of local optimization? Please send them in!{:/comment}

もし局所最適化の例がありましたら、ぜひご連絡ください。

{::comment}
> Wheels within wheels in a spiral array
> A pattern so grand and complex
> Time after time we lose sight of the way
> Our causes can't see their effects.

-- Rush
{:/comment}

> らせん状の通路の中、幾重にも重なり合う輪  
> その模様は壮大で複雑  
> 何度も何度も僕らは途中で視界を失い  
> 原因は思わぬ結果を生み出す

--ラッシュ


{% include video id="u7W0Nm8iHwk?rel=0" provider="youtube" %}

* * *

{% include video id="xJXPUZ0m38g?rel=0" provider="youtube" %}

* * *

[English version](https://seattlescrum.com/local-optimization-bias/)
