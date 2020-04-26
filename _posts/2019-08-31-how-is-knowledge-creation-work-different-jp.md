---
title: "知識創造を行う仕事は、今までの仕事と何が違うのか？（なぜあの会社はコーディングができないのか）"
---
## 知識創造を行う仕事、例えばソフトウェア開発などに見られる根本的な制約は、私たち人間の知識を発見したり創造したりする能力にあります。

{::comment}
English version: https://seattlescrum.com/how-is-knowledge-creation-work-different
## The fundamental constraint of knowledge creation work -- such as software development -- is our ability to discover and create knowledge.

Imagine that you had spent Monday through Thursday working on an essay, a song, or even a computer program. You tore up seven ways that you realized wouldn’t work. You took a walk outside. You slept on it. You did research and found an eighth way that looked like it would work, until you showed it to a friend who pointed out a serious flaw with one part of your idea. By Thursday afternoon you had nearly finished a ninth way that combined the best of your previous approaches and looked to be nearly done. Then Thursday night your cat walked across the keyboard and somehow deleted everything you typed that week.

Would it take you another four days to get back to where you were? Of course not! By 10AM Friday you’d be ahead of where you were Thursday night. Therefore what was the actual constraint on that work? It wasn’t the typing. It was the learning and creation of new knowledge.
{:/comment}

皆さん、一週間かけてエッセー執筆や作詞、あるいはコンピュータプログラム開発などの知的創造取り組む場合をイメージしてみて下さい。様々なやり方を試みましたが上手くいかず、もう７つものアプローチを破棄しました。散歩に出かけては考え、眠りにつく時も考えます。色々とリサーチして今度は上手くいきそうな８つ目のアプローチを閃きましたが、友人に見せると致命的な欠陥を指摘されてしまいました。そして木曜の午後、ついに、これまでの８つのアプローチの優れたところを組み合わせた９つ目の方法がほぼ完成しました。しかしその夜、パソコンのキーボードの上を飼い猫が歩いてしまって、月曜から入力してきた内容が全て消されてしまいました。

![git rm -r](/images/git-rm-r.png){: .align-left width="25%"}

ここから全部作り直すのに、また丸４日間もかかるでしょうか？そんなことはありません。金曜日の朝１０時には、木曜日の夜の状態よりも進んでいるはずです。では、この知識創造における真の制約条件は何だったのでしょうか？タイピング速度ではありません。それは、新しい知識を学び、創造することです。



{::comment}

## Why Johnny, Inc. Can't Write Software

Have you noticed that companies with lots of money and people can't seem to develop software that works very well?  I know interns who can make better websites than certain airlines can.  Those shops aren't built for learning.  They're organized as if software development is just about typing code.  When that fails, they try to fix it with harmful measures: adding incentives and "accountability", creating new roles and departments, hiring even more people to type code.

### Hint: Johnny, Inc. Is Not "Understaffed"

I recently visited a big bureaucratic agency that had trouble doing things that are easy for a small co-located team using modern development practices.  I almost fell over when I heard one of the dozen project managers say "We're understaffed."  No ... that's not the problem.
{:/comment}

## なぜあの会社はソフトウェアのコードが書けないのか

豊富な資金を持ち合わせ、大勢の従業員を抱える会社は、多くの場合、良いソフトウェアを開発できないことをご存知でしょうか？私は、とある航空会社よりもウェブサイト作りが上手いインターンを知っています。このような組織は学習のための組織設計がなされていません。ソフトウェア開発とは単なるコード入力であるかのように組織されているのです。これが立ち行かなくなると、インセンティブや「職務責任」を追加したり、新規役職や部署を作ったり、従業員（コード入力のためにさえ！）を増やしたりといった有害な方法で対処しようとするのです。

### ヒント：問題は「人手不足」ではない

最近、ある巨大な官僚型組織を訪問しました。そこでは、「小規模チームが最新の技術を用いて同一オフィス内で働けば簡単にやってしまう」ような作業に手こずっていました。十数人いるプロジェクトマネージャーの1人が「我々は人手不足なんです」と言うのを聞いた時、私は思わず倒れそうになりました。違います...人手不足が問題なのではありません。
<div class="page-break"></div>

{::comment}
## Implications

What would be different about an organization that recognizes that better software is really about our ability to discover and create knowledge?

| Traditional Organization | Continuous Learning Organization  |
| :----------:|:-------------:|
| people work in separate cubicles, offices, or cities | each small team works at the same table |
| more people | fewer people |
| more roles | fewer roles |
| more departments | fewer departments |
| single-skilled workers | multi-skilled workers |
| [fewer people learn from customers and end users](https://www.youtube.com/watch?v=RAY27NU1Jog) | many people learn from customers and end users |
| private code ([my code/your code](/my-code-your-code/)) practices or policies | internal open-source practices |
| people spend time reading/writing "tickets" | people spend time sharing screens and whiteboards |
| focus on execution, quantity, and velocity | focus on impact |
| learning happens only during brief training periods or on employee's own time | learning happens every day on company time |
| mistakes are not survivable | experimentation is encouraged |
| retrospectives affect teams only |[retrospectives cause improvements to company policies and structure](https://less.works/less/framework/overall-retrospective.html) |
| managers coordinate, reallocate, motivate, and mediate | [managers are capability builders](https://less.works/less/management/role-of-manager.html) |
| extended overtime | adequate sleep |

Becoming a *learning organization* isn't something that gets solved once, by a training program, a reorg, or a one shot "Agile transformation."  It doesn't happen just by talking about organizational culture.  It is a deep change that cannot ignore the policies and structure of the organization. 

{:/comment}
## 意味合い

知識を発見したり創造する能力からより優れたソフトウェアが生まれると認識している組織はは、従来の組織と何が違うのでしょうか？

| 従来の組織 | 継続的に学習していく組織 |
| :----------:|:-------------:|
| 人々が別々のパーティション、オフィス、町で作業 | 小さな各チームが同じテーブルで作業 |
| 大人数 | 少人数 |
| 多数の役割 | 少数の役割 |
| 多数の部署 | 少数の部署 |
| 単一スキルしかない従業員 | 複数スキルを持つ従業員 |
| [顧客やエンドユーザーから学ぼうとしない従業員](https://www.youtube.com/watch?v=RAY27NU1Jog) | 顧客やエンドユーザーから多くを学ぶ従業員 |
| プライベートコード（私が使うコード/あなたが使うコード）の習慣もしくは方針 | 社内オープンソースの習慣 |
| JIRAチケットの読み書きに時間を費やす人 | 画面やホワイトボードをシェアするのに時間を費やす人 |
| 実行、アウトプット向上、およびベロシティ（「４倍」高い生産率）に焦点を当てる | 効果に焦点を当てる |
| 短期トレーニング中やプライベート時間にしか学習できない  | 日々、勤務中に学習できる |
| 失敗が許されない | 実験が奨励される |
| レトロスペクティブがチームにしか反映されない | [レトロスペクティブが企業の方針や構造の改善をもたらす](https://less.works/jp/less/framework/overall-retrospective.html) |
| マネージャーは調整、業務の再配分、動機づけ、仲介を行う | [マネージャーは組織の能力開発をする](https://less.works/jp/less/management/role-of-manager.html) |

学び続ける組織になるには、一回のトレーニングプログラムや組織再編、または単発の「アジャイル変革」では不十分です。組織の文化についてただ話し合えば解決するということでもありません。これには組織の方針や構造を含めた深い変革を要します。

[英語版/English](https://seattlescrum.com/how-is-knowledge-creation-work-different)


