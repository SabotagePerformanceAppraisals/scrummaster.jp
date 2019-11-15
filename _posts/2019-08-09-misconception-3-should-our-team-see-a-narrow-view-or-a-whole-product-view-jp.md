---
title: '大規模組織におけるソフトウェア開発の誤解その３：チームの視野は狭くて良いか、プロダクト全体を見るべきか?'
excerpt: 'ほとんどの企業では、どのプロジェクトについても１１人以上が従事しています。彼らはスクラムを適合させる(局所最適化)ためだけに「プロダクト」を再定義し、プロダクト全体より狭い意味に変えてしまうことがあります。しかしこれは、言葉が本来の意図とは真逆のことを意味してしまう鏡の迷宮への入口なのです。'
header:
  og_image: /images/product-owner-minus-whole-product-authority-equals-team-output-owner.png
  teaser: /images/product-owner-minus-whole-product-authority-equals-team-output-owner.png
---

小さなチームは素晴らしいものです。スクラムの定義上、必須とされるものでもあります。スクラムにおいてはさらにプロダクトバックログ及びプロダクトオーナーも必要です。

ほとんどの企業では、どのようなプロダクトでも１１人以上が従事しています。彼らはスクラムを適合させる（[局所最適化](https://seattlescrum.com/local-optimization-bias)）ためだけに「プロダクト」を再定義し、プロダクト全体より狭い意味に変えてしまうことがあります。しかしこれは、言葉が本来の意図とは真逆のことを意味してしまう鏡の迷宮への入口なのです。

その次に生じるミスは、鋭い人間であればただの「チームバックログ」であると見抜けるものを、「プロダクトバックログ」として各チームに与えてしまうことです。
![プロダクトバックログ　ー　プロダクト全体思考　＝　チームバックログ](/images/product-backlog-minus-whole-product-authority-equals-team-backlog.png){: .align-center width="70%"}

そして、本当は単なる「チームアウトプットオーナー」に過ぎない者を「プロダクトオーナー」として各チームに置いてしまうのです。
![プロダクトオーナー　－　プロダクト全体思考　＝　チームアウトプットオーナー](/images/product-owner-minus-whole-product-authority-equals-team-output-owner.png){: .align-center width="70%"}

その結果残されるのは、各チームが真のプロダクトに対して狭い視野しか持たない、バラバラになった「スクラムチーム」の山です。残念なことに、Henrik Knibergのプロダクトオーナーについての非常に有名な動画でも、最後の方でこの方法が推奨されています（最後の数分間を除けば素晴らしい動画です）。[^1]

![Henrik Kniberg Multiple-PO Dysfunction](/images/henrik-kniberg-multiple-po-dysfunction.png){: .align-center width="40%"}

マネージャーは、自分たちが何とかしない限り、これらのチームが頭を落とされた鶏のように右往左往するのではないかと危惧することになるでしょう。大勢の人間をマネジメントする伝統的手法（少なくともジュリアス・シーザーの軍隊にまで遡るもの）が、ヒエラルキーの導入です。人類はこれを代替する仕組みを考えるのが苦手なようです。結果的に現在我々が「チーフプロダクトオーナー」、「ビジネスオーナー」といった方法を用いているのは、複数のチームアウトプットオーナーの上にある階層の空白を埋めようとしているからなのです。

![Henrik Kniberg Product Owner In a Nutshell Dysfunction](/images/henrik-kniberg-cpo-dysfunction.png){: .align-center width="50%"}

 
「チーフプロダクトオーナー」や「ビジネスオーナー」の名称を用いるということは、不必要な中間層の設定という病の症状が出ているということです。スクラム及びLeSSにおいて、真のビジネス上の決定権者にはシンプルに[プロダクトオーナー](https://less.works/jp/less/framework/product-owner.html)の名称が用いられます。

ラショナル統一プロセス（RUP）は失敗に終わったアプローチですが、その末裔は[大規模アジャイル開発フレームワーク（SAFe）](http://www.lafable.com/)と呼ばれています。SAFeは、我々の「スクラムチーム」の頂上に伝統的マネジメントの層を積み重ねるものです。商業的に成功していますが、それは実際には、伝統的な役職を[アジャイル風に聞こえる役職に改称する](https://fansofless.com)だけのものにすぎないためです。

伝統とアジャイルを混ぜ合わせる以上のようなアプローチは、1つのリストを用いて優先順位を決め、チームを自己組織化させるスクラムよりも、むしろ伝統的な領域において大きな問題を残しました。プロダクトへの視野を狭めてしまうせいで、体で例えるならば、ほんのつま先程度にしかアジャイルを達成できないという点です。体の大部分はまだ、伝統的マネジメントに制約されているということです。

スクラムマスター（及び、存在する場合はマネジメント）は、視野を大きく広げ、[プロダクト全体思考](https://less.works/jp/less/principles/whole-product-focus.html)を促すべきです。

English version is at: <https://seattlescrum.com/misconception-3-should-our-team-see-a-narrow-view-or-a-whole-product-view/>

[^1]: Images from _Product Owner In A Nutshell_ by Henrik Kniberg.
