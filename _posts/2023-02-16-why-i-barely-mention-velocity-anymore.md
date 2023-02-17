---
classes: single
header:
og_image: /images/velocity.png
teaser: /images/velocity.png
---
*Velocity* isn’t part of any Scrum definition that I’m aware of.  The application of "velocity" to software development was invented by eXtreme Programming (XP) pioneers, some of whom now consider it to have been a bad idea.

*ベロシティ*は私の知る限りスクラムの要素ではありません。ソフトウェア開発に「ベロシティ」を適用することは、エクストリーム・プログラミング（XP）の先駆者たちによって考案されましたが、今ではそれが良くないアイデアだと考える人たちもいます。

![Velocity](/images/velocity.png)

Unfortunately, some people in the Scrum world are still pushing things like "400% velocity increase" and "hyperproductivity."  I am embarrassed by this.  This isn't *my* Scrum as I learned from Ken Schwaber, who instead emphasized a rigorous definition of *done* and avoiding promises we can't keep.

残念ながら、スクラムの世界では、いまだに 「4倍のベロシティ向上 」や 「超生産性」などの言葉を押し付けている人がいます。私はこれを恥ずかしく思っています。これは、私が *ケン・シュエイバーから学んだ* スクラムではありません。ケン・シュエイバーは代わりに、 *厳格な完成の定義* と、守れない約束を避けるということを強調していました。

If we’re promoting *the ability to learn and adapt to reality as it’s discovered*, the traditional focus on productivity (whatever that is) can be actively harmful, especially given our nearsightedness (difficulty seeing the whole picture) and cognitive biases towards short termism.  One reason your code cannot be easily changed now is that people were scrambling to get “projects” done, and didn’t create many automated tests, didn’t constantly refactor their code, didn’t pair program, didn't mob program, or didn't even do traditional code reviews.

もし私たちが、 *実験から学び、適応する能力* を促進するのであれば、特に私たちの近視眼性（木を見て森を見ない傾向）と短絡的な認知バイアスを考えると、従来の生産性重視の姿勢は（それがどのような理由であれ）有害となりえます。あなたが昔に書いたコードを簡単に変更できない理由の一つとして、人々が慌てて「プロジェクト」を完了させようとしたことが挙げられます。具体的には、たいした自動テストも作成せず、コードを常にリファクタリングできる状態にもせず、ペアプログラミングやモブプログラミングもせず、従来のコードレビューすら行わなかったということです。

![Velocity Considered Harmful](/images/page-9.png)

Larger organizations struggle even more with the transparency that’s needed for an empirical process to work.  We cannot inspect and adapt the product to customer needs when it isn't integrated, properly tested, and shippable.  When multiple teams are involved in something that’s really one product it can take them years to learn to produce a *done* product increment together every couple weeks.  A focus on velocity pushes these organizations in the wrong direction.
大規模な組織では、経験主義に基づくプロセス制御に必要な透明性の確保にとりわけ苦労します。統合され、適切にテストされ、出荷可能な状態でなければ、プロダクトを顧客のニーズに合わせて検査、適応できないのです。1つのプロダクトに複数のチームが関与している場合、数週間ごとに　*完成* のインクリメントを作成できる状態になるまで、何年もかかることがあります。このような組織は、ベロシティに焦点をあてると誤った方向に進んでしまいます。



![Hyperproductivity Can Hurt](/images/page-10.png)

FBI Sentinel is often cited as an agile success story, and mostly it was.  The part of the story that wasn't told in the *Twice The Hype* books is that real users tried to use it around Sprint 10. And it fell over because it wasn’t until then they discovered their definition of *done* was weak around testing.  So let’s talk more about full testing, less about velocity.

ときどきFBI Sentinelはアジャイルの成功例として挙げられますが、誤った方向へ進んでいました。 *Twice The Hype* の本では語られていませんが、10回のスプリントが終わったころにやっと、顧客がプロダクトに触れられるようになったのです。そして、それは失敗に終わりました。スプリントが10回終わって初めて、彼らの *完成* の定義が、テストに関して弱いことが分かったからです。もうおわかりですよね、完全なテストについてもっと早い段階から、たくさんの対話をする必要があります。ベロシティの向上を求め、ベロシティの話ばかりすると、このような結果になるのです。

![FBI Sentinel Burndown](/images/Sentinel-Burndown.png)

----

QUESTION:
> How do you help companies transition from a “need-to-know-the-date” to “don’t-have-to-answer” mindset?

質問：
> 企業が、「リリース日を求める」体質から「リリース日を検討する必要はない」体質に変わるのに、どのような支援をしてきましたか？

MJ:
> In general the industry trend is toward releasing more frequently.  Keeping the product *always shippable* lends itself to this.  So fixed dates shouldn’t be so scary when our technical practices are right, even if we leave out some lower-valued features because we found higher-valued features along the way.
>
> I won’t say forecasting has zero value, but in real practice there are bigger problems to solve than just that.  When's the last time your release plan was accurate?

MJ:
> 一般に、業界のトレンドは、より頻繁にリリースすることになっています。製品を常に　*出荷可能な状態* にしておくことは、そのための条件となります。ですから、当たり前の品質を担保する技術的な手法が正しく実施されていれば、途中で提供する価値の優先順位をガラガラ変えても、リリース日があることはそれほど怖いものではなくなります。

予測に価値が全くないとは言いませんが、実務ではそれ以上に解決すべき大きな問題があるのです。あなたのリリース計画が最後に正確だったのはいつですか？

----

QUESTION:
> Hi MJ, the thing is : how to plan the delivery of Features over 6 or 9 months when not using velocity? Would you use the number of items done and undone to plan? That would mean you would need two things : 1/ to know all stories that will be developed during these months 2/ to have items with similar size over time => I can't have those two.





質問：
こんにちは、MJさん、教えてください。ベロシティを使わない場合、半年や9ヶ月の納期をどのように計画すればいいのでしょうか？完了した項目と未完了の項目の数を使って計画を立てるのでしょうか？この場合、2つのことが必要になります：①この期間に開発されるすべてのストーリーを知ること
②開発の全期間を通じて、同じような粒度のプロダクトバックログアイテムを持つこと
=> この2つは現実的ではありません。

MJ:
> In theory velocity should help, but in practice the places I've seen that are working on such big batch releases would reduce their risks more by ensuring the whole product is fully tested and integrated every Sprint. Those big batch releases are typically riddled with an uncountable number of bugs and an integration nightmare toward the release date.
>
> After one of these painful release cycles and all the urgent hotfixes and production support emergencies that follow them, I've never
heard someone say "The biggest problem was that we didn't know 9 months ago what features would be included." The biggest problem is the accumulation of low quality code due to your organization's coding, testing, and management habits. Focusing on velocity just makes that *worse*!
>
> I like Yogi Berra's answer: "In theory there's no difference between theory and practice.  In practice, there is."

MJ:
>理論的には、ベロシティは助けになるはずですが、私が見たところ、実際には、このような大きなバッチリリース(半年や９ヶ月の納期)に取り組んでいるところは、プロダクト全体を毎スプリント完全にテストし統合することで、よりリスクを減らすことができるはずです。このような大規模なバッチリリースは、通常、数え切れないほどのバグに悩まされ、リリース日に向けて統合の悪夢が繰り広げられます。

>
>このような痛みを伴うリリースサイクルや、それに続く緊急のホットフィックスやプロダクションサポートの緊急事態の後、私は誰かが「すべての機能をプロジェクト開始前に完璧に定義しておかなかったのが原因だ！」と言ったのを聞いたことがありません。最大の問題は、組織の、コーディング、テスト、マネジメントの習慣（指示命令型）に伴う低品質なコードの蓄積なのです。ベロシティを重視することは、それをさらに *悪化* させるだけです。
>
>私はヨギ・ベラの次の一節が好きです。「理論的には、理論と実践の間には何の違いもない。実践では、この2つは異なる。」


----

QUESTION:
> "Every sprint" is almost like really tiny waterfalls.
>
> How many are shippable with every accepted commit?

質問：
> "スプリント毎"は、ほとんど本当に小さなウォータフォールのようなものです。
>
> コミットを受け入れるごとに、いくつ出荷可能ですか？

MJ:
> Even better! Strive to be like [this team in San Diego](/technical-debt-is-the-high-cost-of-future-change/) that releases live features multiple times a day, usually without bugs.


MJ:
> さらに良い方法があります！[サンディエゴのチーム](/technical-debt-is-the-high-cost of future-change/)のように、一日に何度もライブ機能をリリースし、通常はバグなしにリリースできるように努力することです。

COMMENT (from Adam Gauvin):
> Preach brother!
>
> As a developer, project lead, and occasional scrum master I got to say "velocity" and "burn down" are among keywords to quit usually. It is extremely rare that these align with value delivered.
>
> Seriously anything is better than delusional leadership and lack of vision. Any process deemed agile which disguises ineptitude and ignorance on the premise of presenting added value that isn't actually measurable to upper echelons needs to be eradicated like an *excusez mon francais* plague. Period.
>
> If your company has practices that alienate the lads and lasses in the trenches with working knowledge of what is needed from what they are actually doing you will:
>
> A) lose the most talented ones who can get paid more elsewhere
>
> B) fail to deliver value to the customer
>
> C) over-engineer for the sake of [insert non-descriptive reason]
>
> D) end up with solutions to problems you didn't need to solve
>
> E) waste a lot of time and resources in the name of metrics
>
> F) Finally realize you wasted even more resources on PGMO and/or portfolio management and "being agile" than hiring extra qualified developers that could have actually helped would have cost.


コメント (Adam Gauvinより):
>
> 開発者、プロジェクトリーダー、そして時にはスクラムマスターとして、「ベロシティ」と「バーンダウン」は、不要なキーワードです。これらが提供される価値と一致することは極めて稀です。
>
> 真面目な話、誤った方向へ進むリーダーシップとプロダクトビジョンの欠如よりは、何であってもマシです。上層部に実際に測定できない付加価値を提示するという前提で、無知と無能を隠蔽するアジャイルとみなされるプロセスは、 ペストのように根絶される必要があります。 *私は言いすぎています。ごめんなさい*
>
> もし、あなたの会社に、何が必要かを知っている現場の開発者がいるのに、必要なことを疎外するようなマネージャーがいたら、会社や組織は、より誤った方向へ進んでしまうでしょう。
>
> A) 他の会社でより多くの報酬を得ることができる優秀な人材を会社は失います。
>
> B) 顧客に価値を提供できません。
>
> C) [説明できない理由]のために過剰なエンジニアリングを開発者に行わせています。
>
> D) 解決する必要のない問題の解決に終始します。
>
> E) メトリクス収集の名の下に、多くの時間とリソースを浪費します。
>
> F) 実際に役立つはずの優秀な開発者をより多く雇うよりも、PMOやポートフォリオ管理のために（ベロシティやバーンダウンの計測、チームの報告のために…）多くの無駄なリソースを消費したことに気がつきます。
