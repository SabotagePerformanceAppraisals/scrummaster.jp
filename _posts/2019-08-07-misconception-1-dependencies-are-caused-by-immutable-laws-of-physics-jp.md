---
title: '大規模組織におけるソフトウェア開発に関する誤解　その１：知的作業において「依存関係」が生じるのは、逃れられない物理法則の結果なのか？'
excerpt: "第一次世界大戦の直前、フレデリック・テイラーの同僚であった H・L・ガントは、工程同士の依存関係をはっきり表示するプロジェクト管理表を提案しました。これはガントチャートと呼ばれ、物理的実体によって依存関係が生じる製造・建設・物流等の分野において有用です。"
header:
  og_image: /images/yarn.png
  teaser: /images/yarn.png
---

## 背景

![ヘンリー・L・ガント](../images/henry-l-gantt.jpg){: .align-right width="20%"}
{::comment}
Just before World War I, a colleague of Frederick Taylor named HL Gantt promoted the use of a project schedule chart highlighting activities that depend on each other.  This can be useful in manufacturing, construction, logistics, and other fields where the dependencies are imposed by physical reality.  (Interesting trivia: the Soviet Union tried to use a Gantt chart for it's first five-year plan.)
{:/comment}

第一次世界大戦の直前、フレデリック・テイラーの同僚であった H・L・ガントは、工程同士の依存関係をはっきり表示するプロジェクト管理表を提案しました。これはガントチャートと呼ばれ、物理的実体によって依存関係が生じる製造・建設・物流等の分野において有用です。（余談ですが、旧ソ連でも第一次五カ年計画においてガントチャートを使おうとしていました。）

![SAFeの糸](../images/yarn.svg){: .align-right width="20%"}
{::comment}
Unfortunately, people who haven't discovered that [knowledge work is different from traditional work](/how-is-knowledge-work-different) misapply these techniques to software development.  Software development companies steeped in the project management mindset sometimes try to plan around perceived dependencies with traditional Gantt charts, or sometimes by modeling them with red yarn.  The yarn method is only superficially different than a 100 year old Gantt chart, yet it's still being sold as an "Agile" technique today!
{:/comment}
残念なことに、[知的労働と伝統的労働とは異なる](/how-is-knowledge-work-different-jp)ことを理解せず、ソフトウェア開発にまでこの手法が用いられてしまっています。プロジェクトマネジメント思考に囚われたソフトウェア開発会社は、計画を立てるために、伝統的なガントチャートを用いたり、赤い糸でモデル化したりして、判明している依存関係を考慮に入れようとすることがあります。赤い糸を用いる手法は、百年も使い古されたガントチャートと表面的に異なるだけなのですが、現在でも「アジャイル」なテクニックとして売り込まれています。

{::comment}
## Physical analogies for software development (and other knowledge work) are mental traps
The following real quote reveals the mindset of a project manager with tools to manage dependencies in physical work -- where they actually exist -- but has not written software in a modern way:

> People who think that dependencies are just figments of old-style thinking should convince me by first putting on a shoe and tying the laces, then putting on a sock that goes between their bare foot and the tied shoe without removing the shoe.

{:/comment}

##  ソフトウェア開発（及びその他知的労働）に物理的な例え話を用いるのは、誤解のもとである。

以下に引用したのは実際のコメントです。ソフトウェア開発の現代的な手法を用いずに、物理的労働における依存関係（この種の労働においては現実に存在しますが）の管理ツールを用いようとするプロジェクトマネジャーの考え方を露呈するものです。

>　依存関係が時代遅れの考え方による空想の産物に過ぎないと言うのであれば、まず靴を履き靴紐を結んでから、それを脱がずに素足と靴の間に靴下を履いてみなさい。それができなければ私は納得しない。

{::comment}
## In software development, asynchronous “dependencies” are not caused by immutable laws of physics!

The illusion that we need to plan around "dependencies" through multiple Sprints is a symptom of obsolete organizational structure, policy, and skills. We gain agility by directly addressing those problems rather than institutionalizing them with Gantt charts or red yarn.  The socks and shoes argument inadvertently demonstrates that "dependencies" in software development *are* figments of old-style thinking.

Ten years ago I'd usually hear the same misconception expressed as a *house analogy*:  "If you want to build a house, you have to build the foundation first.  You can't start with the roof."  And this may be true ... about houses.
{:/comment}

## ソフトウェア開発においては、非同期の「依存関係」が生じるのは、逃れられない物理法則の結果ではない。

複数のスプリントを通じた「依存関係」を考慮に入れた計画を立てねばならないと思い込んでしまうのは、組織構造やポリシー、技術が時代遅れとなっている兆候です。これを問題として正面から取り組まなければアジリティは得られず、逆に、ガントチャートや赤い糸で固定化してしまっては解決しません。靴下と靴の例え話は、ソフトウェア開発においては「依存関係」が時代遅れの考え方による空想の産物*である*ことを、迂闊にも露呈しています。

10年前には、同様の誤解を*家の例え話*としてよく耳にしました。「家を建てるには、まず土台から。屋根から建築することはできない」と。これは正しいのでしょうが･･･あくまで、家に限った話です。 


{::comment}
## The fundamental constraint of [knowledge work](/how-is-knowledge-work-different) -- such as software development -- is our ability to discover and create knowledge. 

Imagine that you had spent Monday through Thursday working on an essay, a song, or even a computer program.  You tore up seven ways that you realized wouldn't work.  You took a walk outside.  You slept on it.  You did research and found an eighth way that looked like it would work, until you showed it to a friend who pointed out a serious flaw with one part of your idea.  By Thursday afternoon you had nearly finished a ninth way that combined the best of your previous approaches and looked to be nearly done.

Then Thursday night your cat walked across the keyboard and erased everything you typed that week.

Would it take you another four days to get back to where you were?  Of course not!  By 10AM Friday you'd be ahead of where you were Thursday night.  Therefore what was the actual constraint on that knowledge work? It wasn’t the typing. It was the learning and creation of new knowledge.
{:/comment}


## ソフトウェア開発などの[知識労働](/how-is-knowledge-work-different-jp)における根本的な制約条件は、知識を発見し創造する我々の能力である。

例えば、執筆、作曲、プログラミング等の作業に月曜から木曜までを費やしたとしましょう。いくつもの方法を試しては上手くいきませんでした。散歩してみたり、一晩中考えたりしました。リサーチを行い、次こそ上手くいきそうな８番目の方法を見つけましたが、友人に見せると重大な欠陥を指摘されてしまいました。木曜の午後、これまでの取り組みのいい部分を組み合わせた９番目のやり方がほぼ完成し、ようやく終わりそうなところまで来ました。

そして木曜の夜。あなたの飼い猫がキーボードの上を散歩して、一週間の成果全てが消えてしまいました。

さて、成果を復元するのにまた４日間かかるでしょうか？もちろん違います。金曜の朝１０時には、木曜の夜の状態よりも先に進んでいるでしょう。つまり、この知的労働を現実に制約していたものは何か？キーボード入力ではありません。それは、新しい知識の習得と創造だったのです。


{::comment}
## Perceived "dependencies" in knowledge work are caused by knowledge gaps.

Once we internalize this realization, it leads to actions which were counterintuitive before -- often the opposite actions that project management would advise.  Unfortunately your organization's structure and policies have actively encouraged these knowledge gaps. 

A skillful software development organization allows the Product Owner to *prioritize* the Product Backlog from a business perspective, not just "order" it.  Put away the red yarn.
{:/comment}

## 知識労働において「依存関係」として知覚されるものは、知識のギャップから生じている。

この気づきをしっかりと理解できれば、従来の直感には反するような（そしてしばしばプロジェクトマネジャーのアドバイスとは真逆の）行動に繋がります。不幸なことに、その時まであなたの組織の構造及びポリシーは、知識のギャップを増す方向に機能していたということです。

優れたソフトウェア開発組織であれば、プロダクトオーナーは、プロダクトバックログを*並べ替える*だけではなく、ビジネスの観点から*優先順位をつける*ことが許されています。赤い糸はもう片付けてしまいましょう。

