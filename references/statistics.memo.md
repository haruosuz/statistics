# statistics.memo

**Table of Contents**
- [unclassified](#unclassified)
- [plot](#plot)
- [correlation](#correlation)
- [p-value](#p-value)
- [updates](#updates)
[2019](#2019)
[2018](#2018)
[2017](#2017)
[2016](#2016)
- [hypothesis testing](#hypothesis-testing)
- [Statistics Done Wrong](#statisticsdonewrong) ダメな統計学

----------
## unclassified

https://www.atmarkit.co.jp/ait/articles/1012/07/news103.html
大相撲のアノーマリー （1） (1/2)：実践！ Rで学ぶ統計解析の基礎（7） - ＠IT
![](https://image.itmedia.co.jp/ait/articles/1012/07/r20_dugganLevvitf2.jpg)
明らかに7勝8敗が少なくて、8勝7敗が多い（Levittらの論文から引用）


https://twitter.com/yas_tnk/status/1107028749768286208
Yas on Twitter: "例えばシカゴ大教授Steven Levittの2000年の論文では、日本の相撲における八百長Corruptionを示唆するグラフを、二項分布Binomial Distributionと呼ばれる単純な確率分布で強烈に表現した。八百長が完全に発覚し日本社会で問題になったのはそれから11年も後のことである。 https://t.co/4oXuiBfLKv… https://t.co/GK6EN0TBoP"
5:19 PM - 16 Mar 2019
![](https://pbs.twimg.com/media/D1z0x5XUcAASuWP.jpg)


----------
## plot



### 2018-06

https://twitter.com/sidneymbell/status/1006404852950286336
Sidney Bell on Twitter: "Just finished reading through @ClausWilke's fantastic "Fundamentals of Data Visualization." Clear, helpful, and approachable guide that I wish I'd had when I started my PhD, and I'm sure I'll continue to reference long after I finish. https://t.co/J3CgnMFNOr… https://t.co/rq0nFWcANv"
1:16 AM - 12 Jun 2018

![](https://pbs.twimg.com/media/Dfd32-eUcAE16qC.jpg)

http://serialmentor.com/dataviz/
Fundamentals of Data Visualization
Claus O. Wilke




http://kazumaxneo.hatenablog.com/entry/2019/04/02/073000
データを可視化するwebツール PlotsOfData - macでインフォマティクス
PlotsOfData R / shinyスクリプトをGithub（https://github.com/JoachimGoedhart/PlotsOfData）からダウンロードすると、WebアプリケーションをRまたはRstudioから起動してオフラインで使用できる。

[#barbarplots](http://barbarplots.github.io)
https://twitter.com/hashtag/barbarplots

![https://twitter.com/introspection/status/844903597724913665](https://pbs.twimg.com/media/C7mzT2ZW4AAQ4wZ.jpg:small)

[The Datasaurus Dozen - Same Stats, Different Graphs: Generating Datasets with Varied Appearance and Identical Statistics through Simulated Annealing | Autodesk Research](https://www.autodeskresearch.com/publications/samestats)

![](https://pbs.twimg.com/media/DYVjeN0WkAI8S69.jpg)

![](https://d2f99xq7vri1nk.cloudfront.net/Anscombe_1_0_0.png)



### Weissgerber
https://www.ncbi.nlm.nih.gov/pubmed/25901488
PLoS Biol. 2015 Apr 22;13(4):e1002128. doi: 10.1371/journal.pbio.1002128. eCollection 2015 Apr.
Beyond bar and line graphs: time for a new data presentation paradigm.
Weissgerber TL1, Milic NM2, Winham SJ3, Garovic VD1.

https://twitter.com/leeswijzer/status/592302113725755393
MINAKA Nobuhiro on Twitter: "@leeswijzer この論文の「記述統計量を計算する前に生データを見よ」というメッセージは，有名な〈Anscombe’s quartet〉 http://t.co/A5oiHZt9Dj [Wikipedia] を連想させる．"
8:20 AM - 26 Apr 2015

https://twitter.com/neubig/status/591079565939748864
Graham Neubig on Twitter: "「データを表示する時に、棒グラフと線グラフで平均を見せる代わりに、散布図で各データ点を見せましょう」という論文： http://t.co/T1d5aPZ9k8 。確かに紙面の大きさが同じでも、散布図でデータの分布がよく分かる。 http://t.co/YLOPbXiwBC"
11:22 PM - 22 Apr 2015

![](https://pbs.twimg.com/media/CDPvu5mVEAEpsAl.png)

### anscombe
https://ja.wikipedia.org/wiki/アンスコムの例

![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Anscombe%27s_quartet_3.svg/425px-Anscombe%27s_quartet_3.svg.png)

http://hoxo-m.hatenablog.com/entry/20120214/p1
統計を学びたい人へ贈る、統計解析に使えるデータセットまとめ - ほくそ笑む 
anscombe    ``同じ'' 線形単回帰に対する Anscombe の四つ組


http://d.hatena.ne.jp/hoxo_m/20120214/p1
統計を学びたい人へ贈る、統計解析に使えるデータセットまとめ - ほくそ笑む

	example(anscombe)

http://id.fnshr.info/2012/01/25/whycharts/
統計分析におけるグラフの有用性｜Colorless Green Ideas
- Anscombe, F. J. (1973). Graphs in Statistical Analysis. American Statistician, 27(1), 17–21.




http://aoki2.si.gunma-u.ac.jp/R/dot_plot.html
R -- 群別データ分布図 
```
source("http://aoki2.si.gunma-u.ac.jp/R/src/dot_plot.R")
dot.plot
```

2007/04/09
http://jcb.rupress.org/content/177/1/7
Error bars in experimental biology | JCB
実験生物学におけるエラーバー（SD, SE, CI）の考え方
http://www.kenkyuu2.net/cgi-biotech2/biotechforum.cgi?mode=view;Code=2025
BioTechnicalフォーラム

http://takenaka-akio.org/doc/r_auto/series.html
Rプログラム (TAKENAKA's Web Page) おまけ：さまざまなデータ列の生成



----------
## correlation

https://ja.wikipedia.org/wiki/相関係数
correlation coefficient

http://psy.isc.chubu.ac.jp/~oshiolab/teaching_folder/datakaiseki_folder/02_folder/da02_01.html
心理データ解析第２回(1)

相関係数を用いる際の注意点

検討する仮説に応じて適切にデータ収集を行うことが必要
データの選び方によって相関係数の数値や方向性（＋－）に異なった傾向が生じる場合がある。
（例）男女で相関の±が異なる場合，男女込みで相関係数を算出すると無相関に近づく。
このような場合，男女別で相関を算出する。
関連が群間で異なっている場合，群ごとの相関を分割相関もしくは層別相関という。


2017-06-10
https://togetter.com/li/1119318
全くの偶然による相関関係の図表がなんか笑える「ニコラス・ケイジが映画に出るとプールで人が死ぬ？」 - Togetter

![](https://pbs.twimg.com/media/DB75n2eU0AEenFe.jpg:small)
![](https://images-na.ssl-images-amazon.com/images/I/51qy8YzMWkL._SL400_.jpg)


https://twitter.com/kohske/status/930869204911194112
思い出した、シンプソンのパラドックスだ。 https://togetter.com/li/1014449
1:44 PM - 15 Nov 2017

https://twitter.com/h_okumura/status/930651352052715521
労働時間と知的好奇心には，国レベルでは非常に強い負の相関があるが，個人レベルでは逆に正の相関がある https://oku.edu.mie-u.ac.jp/~okumura/stat/piaac.html
11:19 PM - 14 Nov 2017
https://oku.edu.mie-u.ac.jp/~okumura/stat/piaac.html
PIAACデータ解析
労働時間と知的好奇心に強い負の相関があるというツイートがあり，それに対して疑問の声があった。

結論：国レベルでは，労働時間が増えるほど知的好奇心は減る。個人レベルでは，労働時間が増えるほど知的好奇心は増える。

要するにSimpsonのパラドックスである。国レベルと個人レベルの混同はEcological Fallacy（生態学的誤謬）とも呼ばれる。地域の大人に勉強を教えてもらうと成績が下がる？も参照。

奥村 晴彦
Last modified: 2019-03-17 13:07:49



https://twitter.com/fronori/status/927889710206263301
Tetsuo Ishikawa on Twitter: "Rでの同順位ありスピアマン順位相関ρのp値の計算法について書きました。"Cannot compute exact p-value with ties"とか「タイがあるため、正確なp値を計算することができません」表示に怯まないために。 https://t.co/fj9aa3rw5F"
8:25 AM - 7 Nov 2017

https://togetter.com/li/1014449
生態学的誤謬とシンプソンのパラドックス - Togetter
2016年8月20日

生態学的誤謬とは、全体の傾向（相関など）といくつかに分割した各グループの傾向が食い違ってしまうこと。全体で見たときの相関と、各グループで見た相関は逆転してしまうことがあるんだ。 

![](https://pbs.twimg.com/media/CqQfKiAUAAAdI4D.png:small)

----------

## Simpson's paradox

https://en.wikipedia.org/wiki/Simpson%27s_paradox

![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/Simpson%27s_paradox_continuous.svg/440px-Simpson%27s_paradox_continuous.svg.png)

https://ja.wikipedia.org/wiki/シンプソンのパラドックス

2018-08-31
https://www.krsk-phs.com/entry/simpsonparadox
データ分析の不思議、シンプソンのパラドックスを統計的因果推論から考える - Unboundedly

https://twitter.com/vsbuffalo/status/610953561627852802
Vince Buffalo on Twitter: "And Simpson's Paradox! MT @TRyanGregory: perfect example of why can be very important to take phylogeny into account. http://t.co/rU3stF3soe"
4:34 PM - 16 Jun 2015

![](https://pbs.twimg.com/media/CHqLBtUUYAEUFH4.jpg)

http://jtsutsui.hatenablog.com/entry/20100125/1264353773
シンプソンのパラドックスの図解 - 社会学者の研究メモ

![](http://cdn-ak.f.st-hatena.com/images/fotolife/j/jtsutsui/20100124/20100124024656.png)


----------








----------
## p-value


https://twitter.com/search?q=P値

https://ja.wikipedia.org/wiki/有意
帰無仮説の下で実際にデータから計算された統計量よりも極端な（仮説に反する）統計量が観測される確率を、p値という。


2018.08.19
https://stats.biopapyrus.jp/stats/history-of-statistical-test.html
検定の歴史 | Neyman-Pearson 流の仮説検定が提唱されるまでの歴史
現代において、Fisher 流に基づく検定と Neyman-Pearson 流に基づく検定が共存している。また、これらに加えて、主観確率に基づく Bayes 流の考え方もさかんに使われるようになった。

http://www.jfssa.jp/taikai/2017/table/program_detail/pdf/201-250/10213.pdf
p 値と仮説検定：どう教えればよいか
岡山大学 環境生命科学研究科（環） 坂本 亘



11:12 PM · Sep 13, 2020·Twitter Web App
https://twitter.com/ML_deep/status/1305147368170336257
HELLO CYBERNETICS on Twitter: "統計のプロを謳う人がこれを言っていて、私が "サンプルサイズが大きすぎるのは良くない"というのは、実験とデータ収集にはコストが掛かるのだから"意思決定に必要なサンプルサイズを見積もりましょう"という意味ですよね と確認したら、検定に応じて最適なサイズがあるのだと言われたので、黙った。" / Twitter
それ以前に、サンプルサイズと標本数を混同していたり、統計計算では不偏分散を用いるものだと言っていたり、よく分からん変換をカマしてとりあえず単回帰していたり、正規分布してなかったり直線に乗らないデータは異常だと言ってたり、社会はそういうものかと現実に戻された感があってよかった。

2020/09/13 21:39
https://note.com/nekoumei/n/n3dd00fd25202
「サンプルサイズが大きすぎると良くない」ってどういうこと？｜nekoumei｜note



10:43 PM · Sep 9, 2020
https://twitter.com/momentumyy/status/1303690439883595776
もむ on Twitter: "Q: HARKingと探索的研究の境目はあるのでしょうか？ A: 探索的データ解析の後に仮説を立てるのは普通ですが，その仮説をその解析の前に立てたかのようにすればHARKingです。" / Twitter

https://twitter.com/ykamit/status/1229007107703201793
例の本のサイトに「本論の章タイトルはDon't Say “Statistically Significant” であり，命令形ではっきりと有意性検定を禁止しています．これ以上 p 値を使い続けるということは，最大手の製造元メーカーがリコールし，乗車を禁止している車に乗るのといっしょ」とありますが
アメリカ統計学会監修（？） The American Statistician の「21世紀の統計的推論：“p < 0.05”を超えて」で、禁止しようと言っているのは、p値の二分法的な使用であって、p値の使用を禁止しているわけではありません
8:38 PM · Feb 16, 2020
http://asakura.co.jp/books/isbn/978-4-254-12255-8/
朝倉書店｜ 瀕死の統計学を救え！ ―有意性検定から「仮説が正しい確率」へ―


https://twitter.com/RyoMasahiro/status/1163429419383476224
Masahiro Ryo on Twitter: "No more "statistically significant" The R package "dabestr" is apparently the most comprehensive package for effect size analysis in R, and the original article (1-2 pages) in Nature Methods is worth reading: https://t.co/4WqUhDB90M #pvalue #NHST #Statistics #R https://t.co/43xu4P1OY7"
9:36 PM · Aug 19, 2019

http://interdisciplinary.hateblo.jp/entry/2019/03/24/221251
P値・帰無仮説・有意 - Interdisciplinary
「統計的有意」には弊害があるとして800人以上の科学者が反対を表明 - GIGAZINE
だいぶん、不正確だと思います。

https://twitter.com/KuboBook/status/1166568438225154049
久保拓弥 on Twitter: "豊田秀樹氏による検定論批判――検定・データ解析・データマイニング - Interdisciplinary https://t.co/kDhchFN4hG "帰無仮説の棄却は，危険率を覚悟で仮説を実質的に捨てることであるのに対して，帰無仮説の採択は実質的に態度を留保することである。このような帰無仮説の棄却と採択が対等でない…""
7:29 AM · Aug 28, 2019
http://interdisciplinary.hateblo.jp/entry/20130129/p1
　データの数が増すと，それに伴って「検定力」と呼ばれる確率がいくらでも1に近づいていく。検定力とは，帰無仮説が偽であるときにそれを棄却する確率である。帰無仮説は先に述べたように，元々，厳密には偽だから，データの数が増せば必ず棄却される。



https://twitter.com/utaka233/status/1161284028756111361
utaka on Twitter: "これよく分かんなくなったけど、ここで例になっている対立仮説なしで説明すべき仮説検定ってどんな例なんだろう。z検定は尤度比検定から導出できるものだから違うっぽい？あと対立仮説を準備しない場合の検出力はどうなるんだろう。 https://t.co/f4cKnHzKUC"
11:31 PM · Aug 13, 2019

https://twitter.com/ynakahashi1003/status/1144161577706246145
ynakahashi on Twitter: "これオレもそう思ってたんだけど、最近読んだ生物科学の大久保さんの論文ではFisherの有意性検定とNeyman-Pearsonの仮説検定では帰無仮説の受け入れに対して異なる立場を取る事が書かれてあって、NPの仮説検定では「帰無仮説が棄却出来なかった場合には積極的に帰無仮説を採択する」らしく、混乱してる… https://t.co/eibnsq7nzG"
4:32 AM - 27 Jun 2019

### 2019-03-20

Published:22 May 2019
https://royalsocietypublishing.org/doi/full/10.1098/rsbl.2019.0174
The reign of the p-value is over: what alternative analyses could we employ to fill the power vacuum? | Biology Letters
2. p-Value: how much evidence is there against the null hypothesis?
3. Effect size and confidence interval: how much and how accurate?
4. Bayes factor: what is the evidence for one hypothesis compared to another?
5. Akaike information criterion: what is the best understanding of the phenomenon being studied?
p値 p-value の代替手法4つ
効果量 effect size
信頼区間 confidence interval
ベイズ因子 Bayes factor
赤池情報量規準 Akaike Information Criterion (AIC)

https://twitter.com/KanAugust/status/1111140994593030144
先週話題になっていた例のやつですが、本文の翻訳と思うところをまとめてみました。
"「統計的有意」、「信頼区間」は本当に禁止されるべきなのか"
https://buff.ly/2TE8sVF 
1:40 AM - 28 Mar 2019

https://twitter.com/hshimodaira/status/1109381652243861505
下平英寿 on Twitter: "数理統計の専門家としてマジレスしますと，有限のデータから普遍的な真実を導き出そうっていう帰納的推論は難しいんですよ．仮説検定において頻度論のp値もベイズの事後確率も問題があって，人類はまだ完璧な統計的方法には到達してないです．… "
5:09 AM - 23 Mar 2019

https://twitter.com/NatureDigest/status/1109289618933874688
Nature ダイジェスト、編集部 on Twitter: "800人以上の科学者が「統計学的に有意」という概念そのものを放棄しようと提案。例えばp値という閾値の下なら効果や差が「あり」で上なら「なし」、などということはなく、そのように簡単に結論してはならないのだが、閾値で分けるやり方が蔓延し、多くの人が結果を誤解している現状がある。… https://t.co/D5mPmgSvCQ"
11:03 PM - 22 Mar 2019

https://twitter.com/genkuroki/status/1109084518307098624
黒木玄 Gen Kuroki on Twitter: "#統計 P値の説明がひどすぎ。 P値の正確な定義は「帰無仮説と呼ばれる確率分布に関する仮定(現実世界で成立していなくてもよい)のもとで現実に得られたデータ以上の偏りが生じる確率」。 https://t.co/Sv4rCaXHxc 【実験結果が起こりえる確率が95％以上である場合は、P値は0.05以下になります】"
9:28 AM - 22 Mar 2019

https://twitter.com/h_okumura/status/1109248717645729792
Haruhiko Okumura on Twitter: "この記事のp値の説明は間違っているが，研究者でもこのような誤解をしがちであるということが，p値の弊害の一つだと思う https://t.co/8urcoP2kVQ"
8:21 PM - 22 Mar 2019
p値の意味だけじゃなくてフィッシャーの有意性検定と統計的仮説検定のあたりもごちゃまぜになってしまってますね。

https://twitter.com/gigazine/status/1109047247742763008
GIGAZINE(ギガジン) on Twitter: "「統計的有意」には弊害があるとして800人以上の科学者が反対を表明 https://t.co/xO7OqmkrCM"
7:00 AM - 22 Mar 2019

2019/03/21
https://note.mu/momentumyy/n/nc627a74f4964
若者の有意性検定離れ｜Yuki Yamada｜note

https://twitter.com/koro485/status/1108437257835433986
KRSK on Twitter: "Natureから「統計的有意性」に固執するのをやめようというコメントがオンライン公開されました。世界52カ国、854名からの賛同のサインも公開。 p値自体の価値を否定するものではなく、p < 0.05 or notという２カテゴリーに分類してしまうことが問題であると指摘しています。 https://t.co/848uEsihh0"
2:36 PM - 20 Mar 2019
「統計的有意差がない＝差がない・効果がない」解釈するのはNG！

COMMENT  20 MARCH 2019
https://www.nature.com/articles/d41586-019-00857-9
Scientists rise up against statistical significance

EDITORIAL  20 MARCH 2019
https://www.nature.com/articles/d41586-019-00874-8
It’s time to talk about ditching statistical significance

### 2019-03-20

https://twitter.com/RyuichiroNakato/status/1093149827897077760
「P値の代わりにベイズ・ファクターや別の統計値を使うというのは、結局は真陽性と偽陽性に関する別のトレードオフの方法を選択するということに過ぎません」
P値の問題は氷山の一角でしかない https://qiita.com/KanNishida/items/a91ed14b930bfa2826d9 … #Qiita
9:10 AM - 6 Feb 2019

https://twitter.com/kohske/status/1092944185835937793
p値の扱いは難しいけど、これには目を通しておくべきだと思う。 https://www.jstage.jst.go.jp/article/jjb/38/2/38_153/_article/-char/ja … "科学的知識を深める研究はいくつ もの段階からなっており，統計的検定は，その中の一つに適用される方法にすぎない."
7:32 PM - 5 Feb 2019

https://twitter.com/KevinDKohl/status/1090294240385683465
Got reviewer comments back.
We report a P-values of 0.051 and 0.062. Reviewer: "If it’s not significant, it’s not significant. Delete."
Here's a response I've used in the past, sharing for anyone who might find it useful
12:02 PM - 29 Jan 2019

### 2018

### 2018-02

https://twitter.com/NishikawaMasaru/status/968374116154781696
Masaru Nishikawa on Twitter: "研究結果の再現可能性：The Atlanticにも記事が載ってた。「有意でない研究結果が発表されない問題」、「100研究例の内、97％で統計的に優位な結果が出ていたが、研究結果を再現できたのは36％」「p値を有意（p<0.05）にする研究上の作為的行為（p-hacking）が横行」など。 https://t.co/N3whu5CrWm"
1:35 AM - 27 Feb 2018

https://twitter.com/TJO_datasci/status/968363039698358277
TJO on Twitter: "コーネル大の大学教員が部下に「p = 0.06じゃ論文に出せないぞ、もっと低くしろ」とp-hackingというか捏造をするよう迫ったメールが公開されたと聞いて笑ってる https://t.co/lnltsir8pV"
12:51 AM - 27 Feb 2018

2018-02-13
http://www.ism.ac.jp/events/2018/meeting0213_14.html
小研究会「生態学における統計教育：計算より概念と考え方」
2.「P値とは何だったのか?」 大久保 祐作 (北海道大農）

http://www.esj.ne.jp/meeting/abst/65/S10.html
日本生態学会第65回全国大会 (2018年3月、札幌) 講演要旨
ESJ65 シンポジウム S10
[S10-2] P値とは何だったのか 大久保祐作（北海道大農）
http://www.esj.ne.jp/meeting/abst/65/S10-2.html
しばしば混同されるFisherの有意性検定とNeyman-Pearsonの仮説検定が、異なる目的のための道具であることを確認する

### 2017


6:11 PM - 25 Dec 2018
https://twitter.com/ykamit/status/1077703514707582976
'Yuki' Kamitani on Twitter: "私の周辺でも「プロダクティブな研究者」の多くが単に統計を誤解・誤用してるだけの場合が多い。一方で「とったデータはすべて論文にしてきた」と誇らしげに語る研究者にも注意が必要。「有意な結果」が並んでいるとしたら、HARKingをしている可能性が高い。… https://t.co/vMBt62HgL1"
- HARKingとは、Hypothesizing After the Results are Knownの略語で、データを分析してみて結果を見てから、それにフィットするように仮説を作り、あたかもその仮説がデータ収集よりも先に存在していたかのように論文化していく行為　http://d.hatena.ne.jp/tomsekiguchi/20170727/1501136241
- データを操作してp値をいじる行為を不正と認識している人は多いが、HARKingが不正と思っている人は非常に少ない。私の周辺分野のシニア研究者で理解している人はほぼ皆無（問題を指摘すると一笑に付される）。研究の実践と論文フォーマットの齟齬やフェアプレー精神の問題（？）と理解している人がいた
- HARKingはそういう問題ではなくて、特定のサンプルのパターンにフィットするような仮説は後からいくらでも考えられるが、ノイズにフィットしているだけだとしたら、もう一度実験すればその仮説に合う結果にはならない、という再現性の問題。
- 手元のデータをいじってパターンを探索するのは構わないが、そこから見出した新しい仮説について検定するためには、探索に使ったのとは別のデータが必要。今のデータを捨てて新しいデータをとらないと（統計検定にもとづく）論文にはできない。データを取る前にpre-registrationするともっといい

### 2017

https://tomsekiguchi.hatenablog.com/entry/20170727/1501136241
HARKing, p-hacking, asterisk-seekingを助長している学術界 - 講義のページへようこそ

http://d.hatena.ne.jp/R-statistiker/20170531/1496220635
2017-05-31 アメリカ統計学会「p値」声明文翻訳公開
■[情]「統計的有意性とP値に関するASA声明」

### 2016

2016-03-10
https://www.natureasia.com/ja-jp/ndigest/v13/n6/p値の誤用の蔓延に米国統計学会が警告/75248
Ｐ値の誤用の蔓延に米国統計学会が警告

http://team1mile.com/sjpr59-1/contents_comment/minaka2016/
三中(2016) | 特集「心理学の再現可能性：我々はどこから来たのか　我々は何者か　我々はどこへ行くのか」
三中信宏
統計学の現場は一枚岩ではない
http://team1mile.com/sjpr59-1/wp-content/uploads/2016/07/minaka.pdf
Fisher は対立仮説を設定せずに帰無仮説を検定しようとしたが，Neyman–Pearson は帰無仮説に対置する対立仮説を仮定したというちがいがある（Hacking, 1965；Barnett, 1999）。

http://team1mile.com/sjpr59-1/wp-content/uploads/2016/07/ikeda_hiraishi.pdf心理学における再現可能性危機:問題の構造と解決策 1)
そこで,この状況を打開する方法 として,データを得た後に,それに適合する仮を 構築すること,すなわち HARKing が登場する(Hypothesizing After the Results are Known;Bones, 2012;Kerr, 1998;OʼBoyle, Banks, & Gonzalez- Mule, 2014)。HARKing の弊害は様々に論じられて いるが,おそらく最大の問題点は,それが第一種 の過誤を増大させてしまう点にあると思われる。


https://www.editage.jp/insights/is-my-research-significant-why-you-shouldnt-rely-on-p-values
研究の有意性とは？p値に頼るべきでない理由 | エディテージ・インサイト
2016年09月23日

開催日: 2016/11/24 - 2016/11/25
https://www.jstage.jst.go.jp/article/jscssymo/30/0/30_153/_article/-char/ja/
p値に関する最近の議論
```
p 値は，「効果」がない，あるいは「効果」に差がないとする仮説（帰無仮説）と実際に測定されたデ
ータの不一致性を測る，0-1 の値をとる統計量であり，ゼロに近いほどデータと帰無仮説の乖離を表す．
p 値について，確率であるとの主張があるが，確率ではない（吉村・大森・寒水，2009）．

American Statistical Association（ASA）は，Wasserstein（2016）において p 値にお
ける声明を発表した．内容は以下の原則に基づく．
① p 値はデータが特定の統計モデルとどの程度まで矛盾するかを表し得る．
② p 値は研究対象の仮説が真である確率や，データが偶然によってのみ生成される確率を表さない．
③ 科学的結論とビジネスあるいは政策上の決定は p 値が特定の閾値をパスしたか否かのみによるべ
きでない．
④ 適切な推測には完全な報告と透明性が必要である．
⑤ p 値や統計的有意性は効果の大きさや結果の重要性を測らない．
⑥ p 値それ自身はモデルや仮説に関する証拠のよい測度を与えない．
```

2016年3月11日 (金)
http://elsur.jpn.org/mt/2016/03/002312.html
読書日記: 読了：Wasserstern & Lazar (2016) p値に関するASAの声明について
```
p値とはある特定の統計モデルの下でデータの統計的要約が観察値と同じないしそれより極端になる確率である[←これが超わかりにくいのが、そもそもの元凶なんでしょうね...]。
　(1)p値が示しているのは、データが特定の統計モデルと不整合かどうかだ。
　(2)研究仮説が真である確率でもなければ、データがランダム・チャンスで作られた確率でもない。
　(3)科学的結論やビジネス・政策上の決定を、p値が閾値を超えたかどうかだけで行ってはならない。
　(4)正しい推論のためには完全な報告と透明性が必要だ[と、ここでpハッキングを批判]。
　(5)p値は効果サイズや結果の重要性の指標ではない。 [おっと、効果量の話をするのかな、と思ったけど、そういう話は一切なし。ま、教材じゃないからね]
　(6)p値はモデルなり仮説なりに対する証拠の強さについての良い指標ではない。
```

https://tjo.hatenablog.com/entry/2016/03/08/190000
「p値や有意性に拘り過ぎるな、p < 0.05かどうかが全てを決める時代はもう終わらせよう」というアメリカ統計学会の声明 - 六本木で働くデータサイエンティストのブログ
```
（私訳）
p値は「そのデータがある特定の統計モデルとどれくらい適合しないか」を示し得る
p値は「その仮説が真である確率」は与えないし「ランダムな偶然だけからそのデータが得られる確率」も与えない
科学的結論及びビジネス・政策上の意思決定は「p値がある特定の閾値を切ったかどうか」だけに拠るべきではない
適切な推論は完全な（データ及びモデルに関する）レポーティングと透明性を要するべきである
単一のp値もしくは統計的有意性はその結果の効果や重要性の大きさを測るものではない
p値そのものだけではモデルや仮説に関するエビデンスの良い指標たり得ない
```

### 2015

http://takuyaokada.hatenablog.com/entry/20150606/1433601270
p値ハッキングについての論文を読んだ - tak0kadaの何でもノート

https://www.ncbi.nlm.nih.gov/pubmed/25768323
PLoS Biol. 2015 Mar 13;13(3):e1002106. doi: 10.1371/journal.pbio.1002106. eCollection 2015 Mar.
The extent and consequences of p-hacking in science.

----------
## hypothesis testing

https://ja.wikipedia.org/wiki/仮説検定
一方、検定統計量が危険域の外側にあれば、
帰無仮説を棄却するに足る証拠はないというのがただ一つの結論となる。

https://bellcurve.jp/statistics/course/9311.html
23-2. 検定で使う用語 | 統計学の時間 | 統計WEB
P値が有意水準よりも大きい時は、帰無仮説は棄却されません。これは帰無仮説が正しいと結論づけて良いということを意味しません。検定で用いられる方法は「背理法」なので、「帰無仮説が棄却されない」ことは「帰無仮説が正しいと結論づけて良い」ということにはなりません。この場合、「対立仮説が正しいと結論づけることはできない」ということしか言えないのです。

2019/01/16
https://to-kei.net/hypothesis-testing/about-2/#i-3
”帰無仮説を棄却しない=帰無仮説を受容する”　ではない！

http://id.fnshr.info/wp-content/uploads/sites/2/2014/12/stat_done_wrong.pdf
統計的に有意な差がないことは、差が全然ないことを意味しないのだ。

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6350394/
A Wilcoxon rank sum test, which compared the Dmean values between the two groups (28 genera versus 850 genera), was not statistically significant (p-value = 0.28). This indicates that there was insufficient evidence to conclude that there was a significant difference in intra-genus diversity between “Common BE genera” and “Other genera.” 

https://stats.stackexchange.com/questions/89741/what-to-claim-when-we-dont-reject-the-null-hypothesis
What to claim when we don't reject the null hypothesis? - Cross Validated
"There was insufficient evidence to reject the null hypothesis that CBT increased the amount of sleep at the 5% significance level. The data is consistent with CBT having no effect on insomnia."

2003-06-26
http://takenaka-akio.org/etc/stat_test/
帰無仮説を証明する
帰無仮説が棄却できないのはどんなときか． たとえば，あるパラメータがゼロではないけど その値が小さいためにはっきりゼロじゃないと結論できない場合や， やはりゼロではないけど，データ数が少ないためにゼロじゃないと結論できない場合もある． 検出力不足で帰無仮説が棄却できなかっただけかもしれないのに，帰無仮説が証明されたかのように 論を進めている例も少なくない．

2017年03月16日
https://www.huffingtonpost.jp/nissei-kisokenkyujyo/null-hypothesis-statistics_b_15378064.html
帰無仮説が棄却されないとき－統計的検定で、結論がわかりやすいときには、ご用心：研究員の眼 | ハフポスト
ややこしいのが、帰無仮説に基づいて計算した確率が、有意水準以上であった場合だ。この場合は、帰無仮説は棄却されない。しかし、棄却されないからといって、帰無仮説が正しいと示された訳ではない。
帰無仮説は誤っているとも、正しいとも、示されなかったことになる。この場合、
「有意水準5%では、帰無仮説は棄却されず、誤っているとは言えない、と判断された。」
との結論となる。

----------
### statisticsdonewrong
ダメな統計学

https://id.fnshr.info/wp-content/uploads/sites/2/2014/12/stat_done_wrong.pdf

［訳注 50］効果量 (effect size) とは、効果の大きさを表した量のことである。先に見たように、p 値
は効果の大きさを表した量では・な
・い。それにもかかわらず、効果量でなく、p 値を効果
の大きさを表すのに使ってしまう統計の誤用はしばしば見られる。統計解析を行う人は、
これら 2 つの概念を混同しないように注意する必要がある。


http://id.fnshr.info/2014/12/17/stats-done-wrong-toc/
ダメな統計学：目次｜Colorless Green Ideas

http://id.fnshr.info/2014/12/17/stats-done-wrong-02/
【翻訳】ダメな統計学 (2) データ分析入門｜Colorless Green Ideas
概要
この章は、統計分析でよく用いられるp値という概念について説明している。
http://id.fnshr.info/2014/12/17/stats-done-wrong-02/#toc1
p値は、効果がないか、差異がないという仮定（帰無仮説）のもとで、実際に観測された結果と同じか、それよりも極端な結果が出る確率として定義される。

http://id.fnshr.info/2014/12/17/stats-done-wrong-05/
【翻訳】ダメな統計学 (5) p値と基準率の誤り｜Colorless Green Ideas
概要
この章では、何度も比較を行うことの問題点について扱っている。何度も比較を行えば、本当は存在しない現象が存在するかのように判断されてしまう可能性がある。

https://twitter.com/h_okumura/status/587208093894737920
Haruhiko Okumura on Twitter: "【翻訳】ダメな統計学 (5) p値と基準率の誤り http://t.co/fxx9jPUox9 原文 The p value and the base rate fallacy http://t.co/K9Yp7ULNBe ずいぶん印象が異なる"
6:58 AM - 12 Apr 2015

----------

