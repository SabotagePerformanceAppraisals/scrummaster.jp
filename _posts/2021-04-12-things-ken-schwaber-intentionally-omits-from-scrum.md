---
title: "ケン・シュエーバーが意図的にスクラムから排除したもの"
---

意図的にスクラムの一部とされていないものや、スクラムと矛盾するもの、またスクラムを役立たないものにしてしまうものを挙げてみます。

スクラム警察が来てあなたを牢屋に入れてしまうわけでもありませんし、意図的に何かを排除することに意味があるように思えないかもしれません。ところがスクラムに必要だという思い込みがあると、時に人は、意図せず、気にせずに行動してしまいます。下記のリストに挙げた一件一件について、どういった問題を解決しようとしているのか、そしてあなたのシステムの最適化目標にそった解決法があるのかどうか、考えてください。

スクラムからは下記の事柄が意図的に排除されています。

* [デイリーステータスミーティング](#スクラムにデイリーステータスミーティングは含まれない)
* [ベロシティ](#スクラムにベロシティは含まれない)
* [ストーリーポイント、フィボナッチ数列](#スクラムにストーリーポイントやフィボナッチ数列は含まれない)
* [スクラムオブスクラム](#スクラムにスクラムオブスクラムは含まれない)
* [一つのプロダクトに複数のプロダクトオーナー（例：チーム一つにつき、プロダクトオーナーひとり）](#スクラムには一つのプロダクトにつき一人ののプロダクトオーナーしか存在しない)
* [プロダクトバックログ内のタスク](#スクラムではプロダクトバックログ内にタスクは含まれない)
* [チーフプロダクトオーナーやリリーストレインエンジニアといった余分な役割](#スクラムに余分な役割はない)
* [運営レポートとしてのバーンダウンチャート（またはバーンダウンチャートそのもの）](#スクラムにバーンダウンチャートは含まれない)
* [コーディネーター（調整役）、モーチベーター、または進捗報告者としてのスクラムマスター](#スクラムマスターはコーディネーター調整役やモーチベーターまたは進捗報告者ではない)
* [監視ツールとしてのスプリントバックログ](#監視ツールとしてのスプリントバックログ)

スクラムに当初意図されていたことは、フィードバックループを繋ぎ、仕事をコントロールしやすくするためのフレームワーク及びメタプロセスであることです。あなたが仕事で経験しているスクラムは、これらの意図から離れていったものである可能性が高いと考えられます。


## スクラムにデイリーステータスミーティングは含まれない

ケン・シュエーバーは、[スクラムガイド](/scrum-guide#デイリースクラム)にこう記しました。


>  デイリースクラムの目的は、計画された今後の作業を調整しながら、スプリントゴールに対す る進捗を検査し、必要に応じてスプリントバックログを適応させることである。
>
> 開発者は、デイリースクラムがスプリントゴールの進捗に焦点をあて、これからの 1 日の作業 の実行可能な計画を作成する限り、必要な構造とやり方を選択できる。これは集中を生み出し、 自己管理を促進する。

もうおわかりですね。デイリースクラムを自己組織及び再計画のイベントとみなしていない会社では、デイリーステータスミーティングを、進捗報告するための「スタンドアップ」と呼ぶことになってしまいます。

## スクラムにベロシティは含まれない

ケン・シュエーバーによるスクラムの定義には、ベロシティは含まれていません。ベロシティは時々、エクストリーム・プログラミングの手法から取り入れられることがあります。しかし、ベロシティの発案元であるエクストリーム・プログラミングの人たちさえ、今では後悔している有様です。このままベロシティを続けるべきなのでしょうか？私はそれよりも、プロダクトをいつでも出荷可能な状態にしておくことに集中すべきと考えます。ベロシティに焦点をあてるということは、[部分的な最適化](/local-optimization-bias-jp)であり、これはビジネス成果に悪影響を及ぼします。詳しくは、<https://seattlescrum.com/why-i-barely-mention-velocity-anymore>をご覧ください。

![ベロシティ](/images/velocity.png)

## スクラムにストーリーポイントやフィボナッチ数列は含まれない

スクラムにはいかなる見積もり案も含まれていません。スクラムガイドは、見積もりについてほとんど言及していません。

もちろん、相対見積もりや絶対見積もりについては有益だとみなされる場合も少なくないでしょう。果てしなく続くフィボナッチ数列は本当に必要でしょうか？フィボナッチ数列に秘訣があると聞いて、それを鵜呑みにしてもよいのでしょうか？

二進数を理解する人は、2の冪（べき）で事足りるということに気づくでしょう。見積もりをする際に選択肢が三つを超えるならば、正確なふりをしている可能性が高いといえます。

## スクラムに「スクラムオブスクラム」は含まれない

2001年に出版された最初のスクラム本には、「スクラムオブスクラム」についての記載がありました。それは、組織をアジャイルにする方法を誰も知らないという問題に投げつけられた急拵えの解決案でした。ところが2004年に、ケン・シュエーバーは２作目の著書中で「スクラムオブスクラム」は自己組織するチームと矛盾すると指摘しました。幸いにも、[「スクラムオブスクラム」に代わる手法](/seven-alternatives-to-scrum-of-scrums-jp)はあります。

## スクラムには、一つのプロダクトにつき一人ののプロダクトオーナーしか存在しない

[スクラムの定義](/scrum-guide#スクラムチーム)にはこのように書かれています。

>  スクラムチームが⼤きくなりすぎる場合は、同じプロダクトに専念した、複数のまとまりのあるスクラムチームに再編成することを検討する必要がある。したがって、同じプロダクトゴール、プロダクトバックログ、およびプロダクトオーナーを共有する必要がある。

一つのプロダクトに複数のプロダクトオーナーが存在すると（例：チームごとに別々のプロダクトオーナー）、なぜ害になるのでしょうか。私のスクラム漫画 [「スクラム導入後にアジリティが減少してしまう理由」](/why-scrum-isnt-making-your-company-very-agile) をご参照ください。

そもそも、プロダクトとは何を指すのでしょうか。全体像を捉えるには、[現実的なプロダクトの定義を広げられるだけ広げたもの](https://less.works/jp/less/framework/product)を思い浮かべてください。

## スクラムでは、プロダクトバックログ内にタスクは含まれない

スクラムの要点を得ているかどうかを判断するポイントの一つは、プロダクトバックログにタスクが含まれているか否かです。

スクラムは歴史的に*何を(what)*から*どうやって(how)*を引き離してきました。問題を解決する方法は、自己管理するクロスファンクショナルなチームに委ねられています。もしあなたのチームが「何を」から「どうやって」を引き離せないなら、そのチームはまだ自己管理ができずクロスファンクショナルでもない状態にあるということです。したがって、プロダクトバックログにあるアイテムは、「タスク」ではなくプロダクトバックログアイテム（PBIs）と呼ぶのが適切です。

プロダクトバックログアイテムを「タスク」ではなく「ユーザーストーリー」と呼んでも間違いではないかもしれませんが、「ユーザーストーリー」はさまざまなスクラムチームがエクストリームプログラミングから借りている考え方であるということを念頭に置いておいてください。プロダクトバックログアイテムをうまく作成する方法については、<https://scrumtrainingseries.com/BacklogRefinementMeeting/> をご覧ください。

チームがスプリント計画中にスプリントタスクを作成しようとすることもあるかもしれません（スプリントについては、<https://scrumtrainingseries.com/SprintPlanningMeeting/>をご参照ください）。スクラムでは、「どのように」についての決断を最後の最後まで引き伸ばします。

## スクラムに余分な役割はない

一つのプロダクトにプロダクトオーナーは一人しかいないため、[チーフプロダクトオーナーは存在しません](/comics/volume-1-episode-1/scene-7-there-aint-no-chief-product-owner)。

「リリーストレインエンジニア」というものも存在しません。この役割が、適応性を低下させるのではなくむしろ向上させるようなやり方で、解決すべき問題を解決する方法はあるのでしょうか？作り上げた役割に責任を与えると、自己管理が不十分であまりクロスファンクショナルでもないチームが形成されることになってしまいます。

会社はよく、新しい役割や部署を作ったり構造や手順を新しくしたりして、組織をさらに複雑にすることで問題を解決しようとします。これらの試みには即効性はあるかもしれませんが、害が伴います。スクラムは、組織（会社）の複雑さをできるだけ減らすこと、そして根本的な問題解決に取り組むことを追求します。

## スクラムにバーンダウンチャートは含まれない

2001年に出版されたスクラム本ではバーンダウンチャートが推奨されていました。しかし出版後ほどなく、バーンダウンチャートは見積もりや短期的な効果に焦点を当てすぎてチームの自己管理能力を下げかねないということがわかりました。複雑な仕事はニュートン力学に必ずしも当てはまらないということです。そのためバーンダウンチャートは、その後ずっとスクラムの定義から姿を消したままです。試しにバーンダウンチャートを使ってみると、それがなぜスクラムから姿を消したのかわかるはずです。

## スクラムマスターはコーディネーター（調整役）やモーチベーター、または進捗報告者ではない

スクラムマスターはプロジェクトマネージャーの別名として考案されたものではありません。

調整

スクラムマスターは、調整は*チーム*の責任であるということをチームに教える立場にあります。スクラムマスターが調整役になると、チームは自ら調整をする責任がないと学んでしまいます。

モチベーション（動機）

チームメンバーにモチベーションがなかったら、スクラムマスターが解決に向けて働きかけるべき組織的な障害物があると考えられます。健全な会社では、良い仕事をすること、そしてその仕事がいかに喜んでもらえるかということからモチベーションが生じます。（給料の支払いは生じます。）

進捗報告

アジャイルソフトウェア開発宣言の著者たちは、「動くソフトウェアこそが進捗の最も重要な尺度」 <https://agilemanifesto.org/iso/ja/principles.html>であると述べています 。スクラムにおいては、論理的であることより経験的であることに重きを置きます。*スプリントレビュー*では、プロダクトについてのレポートではなく、実際に動くプロダクトを全員が見ることになります。

スクラムマスターの責任についての詳細は、[スクラムマスターチェックリスト](https://scrummasterchecklist.org/pdf/Scrum-Master-Checklist-jp.pdf) をご覧ください。

## 監視ツールとしてのスプリントバックログ

[スクラムの定義](/scrum-guide#スプリントバックログ)によると、

> スプリントバックログは、開発者による、開発者のための計画である。

とあります。

マイクロソフト勤務の人が、ケン・シュエーバーに「なぜチームの自己管理作成物（例えばスプリントバックログのタスクボードやスプリントバーンダウンチャート）を社内全体に公開するべきではないのか」と質問していたのを耳にしたことがあります。スクラムで定義されている透明性が曲解されていることにお気づきでしょうか。ケンはまず、チームは自己組織するものである、と改めて明言しました。そして、どうしてチーム外の人間がそのチームのスプリント中に干渉したがるのか知りたいものだと付け加えました。

スプリントレビューは、仕事の結果をチーム外に見せる最適な機会です。チーム外からのフィードバックは、その時に歓迎されます。プロダクトオーナーはその後、フィードバックにどのように適応するか決定します。

----
英語版（原文）は、
<https://seattlescrum.com/things-ken-schwaber-intentionally-omits-from-scrum/>でご覧ください。

----

この記事を翻訳するにあたり、[荒瀬 中人氏](https://www.linkedin.com/in/nakato-arase-6a8b28135/)と[今西 健太氏](https://www.linkedin.com/in/kenta-imanishi-55697220b/)よりご協力をいただきました。