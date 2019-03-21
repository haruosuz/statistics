Haruo Suzuki (haruo[at]g-language[dot]org)  
Last Update: 2019-03

----------

# Statistics
**統計学**

## Table of Contents
- [featuring](#featuring)
- [updates](#updates)
  - [2019](#2019)
  - [2018](#2018)
  - [2017](#2017)
  - [2016](#2016)
- [batch effect](#batch-effect)
- [Causal inference](#causal-inference)
- [Confidence interval](#ci)
- [contingency table](#contingency-table)
- [DoE](#doe)
  - [Dummy](#dummy)
- [hypothesis testing](#hypothesis-testing)
- [meta-analysis](#meta-analysis)
- [multiple comparison](#multiple-comparison)
- [ordination](#ordination) PCA PCoA MDS
  - [mds](#mds)
- [ROC](#roc)
- [sample](#sample)
  - [sample size](#sample-size)
  - [n=3](#n3)
- [statistical_significance](#statistical_significance)
- [plot](#plot)
- [references](#references)
 - [Colorless Green Ideas](#colorless-green-ideas)
- [toukei-kentei](#toukei-kentei)
- [link](#link)
- [people](#people)
  - [Dr. KID](#dr-kid)
  - [leeswijzer](#leeswijzer) MINAKA Nobuhiro
  - [yusuke_tsugawa](#yusuke_tsugawa)
  - [tmaita77](#tmaita77)
- [p-value](#p-value)
- [books](#books)
  - [Statistics Done Wrong](#statisticsdonewrong) ダメな統計学


----------
## featuring

http://www.snap-tck.com/room04/c01/stat/stat10/stat1003.html
10.3 ロジスティック回帰分析の計算方法
(1) 最小2乗法を利用する方法
(2) 最尤法を利用する方法

https://twitter.com/bayesjuku
https://twitter.com/hashtag/bayesWS3rd

2017/07/02
https://to-kei.net/basic/history/
統計学の歴史〜古代ローマから現代まで〜 | 全人類がわかる統計学

http://techlife.cookpad.com/entry/2016/09/26/111601
仮説検証とサンプルサイズの基礎 - クックパッド開発者ブログ

https://www.atmarkit.co.jp/ait/articles/1012/07/news103.html
大相撲のアノーマリー （1） (1/2)：実践！ Rで学ぶ統計解析の基礎（7） - ＠IT
![](https://image.itmedia.co.jp/ait/articles/1012/07/r20_dugganLevvitf2.jpg)
明らかに7勝8敗が少なくて、8勝7敗が多い（Levittらの論文から引用）

----------
## updates

### 2019

https://www.nature.com/articles/d41586-019-00857-9
Scientists rise up against statistical significance
https://twitter.com/koro485/status/1108437257835433986
KRSK on Twitter: "Natureから「統計的有意性」に固執するのをやめようというコメントがオンライン公開されました。世界52カ国、854名からの賛同のサインも公開。 p値自体の価値を否定するものではなく、p < 0.05 or notという２カテゴリーに分類してしまうことが問題であると指摘しています。 https://t.co/848uEsihh0"
2:36 PM - 20 Mar 2019
「統計的有意差がない＝差がない・効果がない」解釈するのはNG！

https://twitter.com/yas_tnk/status/1107028749768286208
Yas on Twitter: "例えばシカゴ大教授Steven Levittの2000年の論文では、日本の相撲における八百長Corruptionを示唆するグラフを、二項分布Binomial Distributionと呼ばれる単純な確率分布で強烈に表現した。八百長が完全に発覚し日本社会で問題になったのはそれから11年も後のことである。 https://t.co/4oXuiBfLKv… https://t.co/GK6EN0TBoP"
5:19 PM - 16 Mar 2019
![](https://pbs.twimg.com/media/D1z0x5XUcAASuWP.jpg)

http://yamano357.hatenadiary.com/entry/2019/03/15/090000
『女子高生乱子によるベイズ統計学入門講座』を読みました（恵贈お礼） - バイアスと戯れる

https://twitter.com/matsui_kota/status/1105392307161841664
Kota Matsui on Twitter: "京大の生物統計の講義コースの動画が無料公開されている（https://t.co/CD74HHpQzp）。昨今指摘されているp値問題についてまるまる1回割いて解説しているなど生物統計じゃない人でも視聴の価値はあるかもしれない"
4:57 AM - 12 Mar 2019


https://twitter.com/search?q=統計学はときにセクシーな学問で
http://www.lifescience.co.jp/shop2/index_0172.html
統計学はときにセクシーな学問である | ライフサイエンス出版
【著】 デビッド・シュピーゲルハルター
【訳】 石塚直樹

https://gendai.ismedia.jp/articles/-/59944?media=bb
ブルーバックス伝説の名著『統計でウソをつく法』100刷突破！（ブルーバックス編集部） | ブルーバックス | 講談社（1/3）
2019年3月4日付

https://twitter.com/Ri7_u10/status/1101320072943919104
```
☑︎「サンプルサイズ／標本の大きさ」のことを「サンプル数」と言わない
☑︎「期待」の意味で「期待値」を使わない
☑︎「母集団の大きさ」あるいは「分母」の意味で「母数」を使わない
10:15 PM - 28 Feb 2019
```

### 2018

https://twitter.com/ykamit/status/1077703514707582976
'Yuki' Kamitani on Twitter: "私の周辺でも「プロダクティブな研究者」の多くが単に統計を誤解・誤用してるだけの場合が多い。一方で「とったデータはすべて論文にしてきた」と誇らしげに語る研究者にも注意が必要。「有意な結果」が並んでいるとしたら、HARKingをしている可能性が高い。… https://t.co/vMBt62HgL1"
6:11 PM - 25 Dec 2018

私の周辺でも「プロダクティブな研究者」の多くが単に統計を誤解・誤用してるだけの場合が多い。一方で「とったデータはすべて論文にしてきた」と誇らしげに語る研究者にも注意が必要。「有意な結果」が並んでいるとしたら、HARKingをしている可能性が高い。

HARKingとは、Hypothesizing After the Results are Knownの略語で、データを分析してみて結果を見てから、それにフィットするように仮説を作り、あたかもその仮説がデータ収集よりも先に存在していたかのように論文化していく行為　

http://d.hatena.ne.jp/tomsekiguchi/20170727/1501136241
HARKing, p-hacking, asterisk-seekingを助長している学術界

データを操作してp値をいじる行為を不正と認識している人は多いが、HARKingが不正と思っている人は非常に少ない。私の周辺分野のシニア研究者で理解している人はほぼ皆無（問題を指摘すると一笑に付される）。研究の実践と論文フォーマットの齟齬やフェアプレー精神の問題（？）と理解している人がいた

HARKingはそういう問題ではなくて、特定のサンプルのパターンにフィットするような仮説は後からいくらでも考えられるが、ノイズにフィットしているだけだとしたら、もう一度実験すればその仮説に合う結果にはならない、という再現性の問題。

手元のデータをいじってパターンを探索するのは構わないが、そこから見出した新しい仮説について検定するためには、探索に使ったのとは別のデータが必要。今のデータを捨てて新しいデータをとらないと（統計検定にもとづく）論文にはできない。データを取る前にpre-registrationするともっといい

でも、これを受け入れられない人が多くて、他グループの発表で指摘して、ハラスメント扱いされたことは何度もある

### 2018-09

http://kusanagi.hatenablog.jp/entry/2018/09/06/185559
ひとに統計相談をするための8つの基本的なTips - 草薙の研究ログ

### 2018-07

https://twitter.com/strnr/status/1024286159747342336
Stephen Turner on Twitter: "Using summary statistics to determine whether a non-significant result supports the absence of an effect https://t.co/SeuzU8atpt… https://t.co/Q8dapoaQh7"
9:30 AM - 31 Jul 2018
https://blog.usejournal.com/using-summary-statistics-to-determine-whether-a-non-significant-result-supports-the-absence-of-an-1ff61e97f7cf

2018年7月13日
http://team1mile.com/sjpr61-1/
特集「統計革命」 | Make Statistics Great Again

http://team1mile.com/sjpr61-1/contents_original/
目次（原著論文） | 特集「統計革命」

https://twitter.com/asarin/status/1017503473779163136
『心理学評論』第61巻1号「統計革命 Make Statistics Great Again」公刊
原著論文9本（「オープンサイエンス」「モデリング」「仮説評価」）とコメント論文3本（と巻頭言）の13本を，特集Webサイトからご覧いただくことができます．
http://team1mile.com/sjpr61-1/ 
4:18 PM - 12 Jul 2018


### 2018-06

https://twitter.com/sidneymbell/status/1006404852950286336
Sidney Bell on Twitter: "Just finished reading through @ClausWilke's fantastic "Fundamentals of Data Visualization." Clear, helpful, and approachable guide that I wish I'd had when I started my PhD, and I'm sure I'll continue to reference long after I finish. https://t.co/J3CgnMFNOr… https://t.co/rq0nFWcANv"
1:16 AM - 12 Jun 2018

![](https://pbs.twimg.com/media/Dfd32-eUcAE16qC.jpg)

http://serialmentor.com/dataviz/
Fundamentals of Data Visualization
Claus O. Wilke

### 2018-03

https://twitter.com/leeswijzer/status/978742721627279362
MINAKA Nobuhiro on Twitter: "［欹耳袋］椎名乾平 2016. 相関係数の起源と多様な解釈．心理学評論 59(4): 415-444 https://t.co/nku5J1ZWLM [open access] ※「はじめに」（p. 415）では，統計学史のもつ意義に関するとても重要な点が指摘されていて，ワタクシは深く深く共感する．"
5:17 PM - 27 Mar 2018

http://d.hatena.ne.jp/MikuHatsune/20180321/1521639267
（臨床系の）統計解析でやらかしがちな10個のミス - 驚異のアニヲタ社会復帰への道

https://twitter.com/M123Takahashi/status/974471731183157248
高橋将宜 Masayoshi Takahashi on Twitter: "P値の問題は、すでに1999年の段階でGill (1999)やJohnson (1999)が指摘していたにも関わらず、実際に大きな問題として取り上げられたのは近年になってからで、実に20年近くもかかっていますね。 Gill (1999) https://t.co/8GU7mTemWs Johnson (1999)：pdf直リンク https://t.co/G6pytQi9Oz… https://t.co/umWCKqjyxN"

https://gigazine.net/news/20180316-guinness-and-his-statistical-legacy/
ギネスビールの醸造所が統計学的手法の一つ「t検定」を生み出した - GIGAZINE

### 2018-02

1:35 AM - 27 Feb 2018
https://twitter.com/NishikawaMasaru/status/968374116154781696
Masaru Nishikawa on Twitter: "研究結果の再現可能性：The Atlanticにも記事が載ってた。「有意でない研究結果が発表されない問題」、「100研究例の内、97％で統計的に優位な結果が出ていたが、研究結果を再現できたのは36％」「p値を有意（p<0.05）にする研究上の作為的行為（p-hacking）が横行」など。 https://t.co/N3whu5CrWm"

12:51 AM - 27 Feb 2018
https://twitter.com/TJO_datasci/status/968363039698358277
TJO on Twitter: "コーネル大の大学教員が部下に「p = 0.06じゃ論文に出せないぞ、もっと低くしろ」とp-hackingというか捏造をするよう迫ったメールが公開されたと聞いて笑ってる https://t.co/lnltsir8pV"

2018-02-13
http://www.ism.ac.jp/events/2018/meeting0213_14.html
小研究会「生態学における統計教育：計算より概念と考え方」
P値とは何だったのか
http://www.esj.ne.jp/meeting/abst/65/S10.html

https://www.yodosha.co.jp/smart-lab-life/statics_pitfalls/statics_pitfalls12.html
第12回 統計データ解析の地上世界と天空世界 ―連載の総括として （2018/02/02公開）

第1回 データ解析の第一歩は計算ではない （2017/11/10公開）

----------
### 2017

http://www.sg.med.osaka-u.ac.jp/school_2017.html
遺伝統計学・夏の学校＠大阪大学（2017）
－ 講義資料

![](http://www.sg.med.osaka-u.ac.jp/files/StatGeneSummerSchool_2017.png)

2017-07-27
http://d.hatena.ne.jp/tomsekiguchi/20170727/1501136241
HARKing, p-hacking, asterisk-seekingを助長している学術界 - 講義のページにようこそ

2017-06-10
https://togetter.com/li/1119318
全くの偶然による相関関係の図表がなんか笑える「ニコラス・ケイジが映画に出るとプールで人が死ぬ？」 - Togetter

![](https://pbs.twimg.com/media/DB75n2eU0AEenFe.jpg:small)
![](https://images-na.ssl-images-amazon.com/images/I/51qy8YzMWkL._SL400_.jpg)

### 2017-05
http://d.hatena.ne.jp/R-statistiker/20170531/1496220635
2017-05-31 アメリカ統計学会「p値」声明文翻訳公開
■[情]「統計的有意性とP値に関するASA声明」

----------
### 2016

2016-03-10
https://www.natureasia.com/ja-jp/ndigest/v13/n6/p値の誤用の蔓延に米国統計学会が警告/75248
Ｐ値の誤用の蔓延に米国統計学会が警告

http://team1mile.com/sjpr59-1/contents_comment/minaka2016/
三中(2016) | 特集「心理学の再現可能性：我々はどこから来たのか　我々は何者か　我々はどこへ行くのか」
三中信宏
統計学の現場は一枚岩ではない
http://team1mile.com/sjpr59-1/wp-content/uploads/2016/07/minaka.pdf

http://team1mile.com/sjpr59-1/wp-content/uploads/2016/07/ikeda_hiraishi.pdf
心理学における再現可能性危機:問題の構造と解決策 1)
そこで,この状況を打開する方法 として,データを得た後に,それに適合する仮を 構築すること,すなわち HARKing が登場する
(Hypothesizing After the Results are Known;Bones, 2012;Kerr, 1998;OʼBoyle, Banks, & Gonzalez- Mule, 2014)。HARKing の弊害は様々に論じられて いるが,おそらく最大の問題点は,それが第一種 の過誤を増大させてしまう点にあると思われる。

----------

https://twitter.com/KuboBook/status/972394855161765888
久保拓弥 on Twitter: "なぜか過剰に製本された「統計数理」Vol.64-1「生態学における統計モデリング」https://t.co/Q8Vbb0kQak ……水曜日 (3/14) の自由集会では無料配布して在庫一掃する予定！… "
http://www.ism.ac.jp/editsec/toukei/pdf/64-1-001.pdf
統計数理(2016)

http://hosho.ees.hokudai.ac.jp/~kubo/memo/seibutukagaku/kubostat.pdf
樹木・森林生態学「よく出る」誤用統計学の基本わざ
久保拓弥


----------
### 2015

http://takuyaokada.hatenablog.com/entry/20150606/1433601270
p値ハッキングについての論文を読んだ - tak0kadaの何でもノート








----------
## p-value

https://twitter.com/search?q=P値

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

----------
## books

http://kosugitti.net/archives/5958
犬4匹本出版にあたって – Kosugitti's BLOG

### statisticsdonewrong

https://www.statisticsdonewrong.com/
Statistics Done Wrong

https://twitter.com/h_okumura/status/587208093894737920
Haruhiko Okumura on Twitter: "【翻訳】ダメな統計学 (5) p値と基準率の誤り http://t.co/fxx9jPUox9 原文 The p value and the base rate fallacy http://t.co/K9Yp7ULNBe ずいぶん印象が異なる"
6:58 AM - 12 Apr 2015

http://www.keisoshobo.co.jp/book/b272873.html
ダメな統計学 - 株式会社　勁草書房

第3章　擬似反復：データを賢く選べ
　3.3　バッチ生物学

![](http://www.keisoshobo.co.jp//images/book/272873.jpg)

http://keisobiblio.com/2017/01/25/atogakitachiyomi_damenatokeigaku/
あとがきたちよみ／『ダメな統計学　悲惨なほど完全なる手引書』 - けいそうビブリオフィル

http://hidekatsu-izuno.hatenablog.com/entry/2017/02/12/022842
「ダメな統計学」お勉強メモ - hidekatsu-izuno 日々の記録

http://id.fnshr.info/2014/12/28/stats-done-wrong-ja-pdf/
『ダメな統計学』冊子PDFの公開｜Colorless Green Ideas

http://id.fnshr.info/2016/03/28/excel-bad-charts/
Excelのダメなグラフでウソをつく法｜Colorless Green Ideas

http://id.fnshr.info/2015/11/07/math-class-4-stats/
統計を勉強するときに数学に悩まされる人のための一冊｜Colorless Green Ideas

http://id.fnshr.info/2014/12/17/stats-done-wrong-toc/
ダメな統計学：目次｜Colorless Green Ideas

http://id.fnshr.info/2014/12/17/stats-done-wrong-13/
【翻訳】ダメな統計学 (13) 終わりに｜Colorless Green Ideas

実験が終わった後に統計学者に相談することは、しばしば単に検死を頼むようなものになる。統計学者は、何のせいで実験が死んだのかについて言うことができるかもしれない。

p値を普及させた人、R. A.フィッシャー [3]
![](http://id.fnshr.info/wp-content/uploads/sites/2/2014/12/r-a-fischer.jpg)

## BDS

http://apprize.info/data/bioinformatics/1.html
How to Learn Bioinformatics - Ideology: Data Skills for Robust and Reproducible Bioinformatics - Bioinformatics Data Skills (2015)

Pay Attention to Experimental Design

To consult the statistician after an experiment is finished is often merely to ask him to conduct a post mortem examination. He can perhaps say what the experiment died of.

R.A. Fisher

https://github.com/haruosuz/books/tree/master/bds#pay-attention-to-experimental-design

----------
## Mendelian randomization
https://en.wikipedia.org/wiki/Mendelian_randomization

https://www.technologyreview.jp/s/102737/researchers-find-a-way-to-mimic-clinical-trials-using-genetics/
MIT Tech Review: 遺伝学から効き目を予測、「メンデルランダム化」で変わる新薬開発

http://blog.livedoor.jp/megikaya/archives/51348455.html
Mendelian randomizationの原理 : 知識の卵

http://jojoshin.hatenablog.com/entry/2017/12/04/175120
Mendelian randomization（メンデルランダム化）とは - 統計学と疫学と時々、助教生活

http://www.igaku-shoin.co.jp/paperDetail.do?id=PA03226_02
医学書院／週刊医学界新聞(第3226号 2017年06月05日)



----------
### batch effect

(Oct. 2016)
http://bukai.pharm.or.jp/bukai_kozo/SARNews/SARNews_31.pdf
非生物学的な(意味のない!)共発現関係が生 じる原因のいくつかは、RNA の品質や batch effect に帰する。batch effect とは、サンプルを得 る時期が異なった場合や別の研究室で行われた場合に、データ取得の際に発生する実験品質の 違いがオミックスデータに生じることを指す(特に大規模な実験では、不可避な変動である)。 通常、これらバイアスの推定と影響の緩和は、実験デザインに基づいた線形モデルによって行 うことができ、重要視されるようになっている。実際、我々も 50 種のシロイヌナズナ変異体 のメタボロームデータ解析の際には、このような batch effect を考慮した [11]。

2016年8月3日
http://postd.cc/ten-simple-rules-for-effective-statistical-practice/
効率的な統計実践のための、10個のシンプルなルール | コンピュータサイエンス | POSTD
ルール7：変動性を評価する
データを集めるのが別の日、別の研究室、あるいは手順を若干変え得るということであれば、考慮すべき変動性の潜在的要因が3つ以上あります。マイクロアレイ分析においてはバッチ効果が変動性の追加をもたらすものとしてよく知られており、フィルタをかけるのにはいくつかの方法があります。

http://fgfwww.nibb.ac.jp/wiki5/data/media/git2013sopen/1.3-nibb_training_course_2013s_1-3.pdf
実験デザインの重要性
•-omicsデータは”batch effect”という体系的なバイアスが多くの場合、混入する。

- 線形モデルで推定・除去
  - 遺伝子型/処理など注目している効果の要因
  - 反復(実験日時)/実験者 などバイアス要因

http://www.iwlab.org/our-lab/our-staff/yy/sympo/20121109
Batch effectとは，実験環境 (機器や観測者など) の違いで生じるデータ変動 (variation) のことで，データを統合して解析を進める際には，このBatch effectが悪さをするという話をされていた．例えば，マイクロアレイデータ一つを取ってみても，遺伝子発現を測定する方法が異なる機械はいくつも存在しており，それぞれで得られたデータは，固有のBatch effect を持ってしまう．

Oct 14, 2012
https://www.slideshare.net/antiplastics/meta-analysis-14720694
Meta analysis of microarray
弘毅 露崎
 batch effect補正

----------
## Causal inference
**因果推論**

http://kamonohashiperry.com/archives/531
統計的因果推論に関するスライドとRのサンプルコード | かものはしの分析ブログ

http://tjo.hatenablog.com/archive/category/統計的因果推論
統計的因果推論 カテゴリーの記事一覧 - 六本木で働くデータサイエンティストのブログ

2018年03月04日
https://qiita.com/kaizu_3324/items/16a86b2aa342084be44f
統計的因果推論とPropensity Score（傾向スコア）④ 
https://qiita.com/kaizu_3324

https://twitter.com/call_me_nots/status/953441739804569600
nots™ on Twitter: "“統計的因果推論への招待 -因果構造探索を中心に- - SlideShare” https://t.co/mLGB7oQAu8"
8:39 PM - 16 Jan 2018

2017-12-30
http://krsk-phs.hatenablog.com/entry/pure_criticism
炭水化物は体に悪い？脂質をたくさん摂るほど健康に良い？：2017年世界一に選ばれた科学論文を解説 - Unboundedly

https://twitter.com/koro485
ヒトの行動や健康に関するデータ分析・因果推論に興味がある研究者見習い@博士課程@ボストン ↓個人ブログ

2017-09-30
http://jairo.nii.ac.jp/0069/00037618
＜特集＞比較政治学における因果推論
久保慶一
https://www.waseda.jp/fpse/pse/assets/uploads/2014/05/df3ed38f795bf40b63002e3b3c406b71.pdf

Jul 14, 2017
https://www.slideshare.net/sshimizu2006/ss-77876940
統計的因果推論への招待 -因果構造探索を中心に-

http://hosho.ees.hokudai.ac.jp/~kubo/ce/2017/Hayashi17ESJcausal.pdf
2017年3月15日 18:00-20:00 生態学会自由集会 『データ解析で出会う統計的問題:原因→結果の統計モデリング』
生態学者のための統計的因果推論入門 : 重回帰の結果に基づき「介入」する前に
【後日配布版スライド】
林 岳彦 国立環境研究所環境リスク・健康研究センター

2016年8月11日
https://rpubs.com/nakamichi_/study-iwanami-ds3
岩波データサイエンスvol.3のデータで遊ぼう

2016年3月16日
http://www.socialpsychology.jp/seminar/seminar_160316.html
日本社会心理学会
第3回春の方法論セミナー「統計的因果推論への招待」
動画
「因果と確率の哲学」大塚淳
https://www.youtube.com/watch?v=SlPFbKz1Nm4
「ぼくらが因果鉄道の旅に出る理由」林岳彦
https://www.youtube.com/watch?v=1KTXcHrA8K8

Jul 30, 2016
https://www.slideshare.net/shuyo/doraemon-causality-64540448
ドラえもんでわかる統計的因果推論 #TokyoR
Shuyo Nakatani

http://hikaru1122.hatenadiary.jp/entry/2016/05/12/212857
統計的因果推論の勉強会の前準備 - Knowledge As Practice

https://healthpolicyhealthecon.com/2014/09/30/study-design-overview/
因果推論？記述統計？－まずは研究デザインをはっきりさせよう – 医療政策学×医療経済学
「因果推論」（Causal inference）

http://d.hatena.ne.jp/isseing333/20120330/1333118828
因果推論のススメ - アイアナ：データ分析や人工知能(AI)などの技術雑記

----------
## CI
*Confidence interval*

https://ja.wikipedia.org/wiki/信頼区間

https://twitter.com/h_okumura/status/953470664714862592
Haruhiko Okumura on Twitter: "正確に説明してある。長い目で見て95%正しいが，具体的なデータから求めた95%信頼区間はその中に真の値が95%の確率で含まれるわけではない（というのが非ベイジアンの解釈） https://t.co/FPxnYVZZTl"
10:34 PM - 16 Jan 2018

http://id.fnshr.info/2017/03/13/dena-conf-intv/
DeNA に対する第三者委員会の調査報告書での信頼区間の説明｜Colorless Green Ideas


信頼区間って何？
http://oku.edu.mie-u.ac.jp/~okumura/stat/what_is_CI.php

 http://www.anlyznews.com/2012/02/blog-post_08.html
「統計学を拓いた異才たち」で触れる統計学史
信頼区間を考えてみよう。これは、何回も推定を繰り返したとして、真のパラメーターが信頼区間におさまっている割合が、例えば95%である事を意味する。しかし、推定量の正しさの度合いが95%だとか、標本の95%がおさまる範囲だと解釈してしまう人は少なく無い（信頼区間って何？）。

----------
## contingency table

https://en.wikipedia.org/wiki/Contingency_table

https://ja.wikipedia.org/wiki/分割表
付随性がない場合、2つの変数は「独立」(independent) と見ることができる。

http://daas.la.coocan.jp/GLM/7_keisuu_data.htm
計数データの解析

　少し混乱してしまうかもしれないが、一言でいえばカテゴリカル型である計数データとは独立な個々の要素の計数である、ということである（だから、重複してカウントされたデータはもはや計数データとはいえない）。

https://support.minitab.com/ja-jp/minitab/18/help-and-how-to/statistics/tables/how-to/chi-square-test-for-association/before-you-start/data-considerations/
関連性のカイ二乗検定のデータに関する考慮事項 - Minitab

すべてのデータが重複なしで、相互に排他的なカテゴリに分類されなければならない
関連性のカイ二乗検定は、変数カテゴリが重複する場合は実行できません。したがって、各観測値は1つまた唯一のカテゴリに分類されます。

https://support.minitab.com/en-us/minitab/18/help-and-how-to/statistics/tables/how-to/chi-square-test-for-association/before-you-start/data-considerations/
Data considerations for Chi-Square Test for Association - Minitab

All the data must be categorized into mutually exclusive categories, with no overlap
The chi-square test of association cannot be performed when categories of the variables overlap. Thus, each observation must be categorized into one and only one category.

----------
## DoE
Design of experiments

https://ja.wikipedia.org/wiki/実験計画法
基本原則
- 局所管理化
- 反復
- 無作為化（ランダム化）
以上でも制御できない可能性のある要因の影響を除き、偏りを小さくするために条件を無作為化する。例えば実験を行う空間的・時間的順序の影響があるかもしれないから、決まった順序でなく実験のたびに無作為に順序を決めるなど。これは生物学などの実験で特に重要である。
以上の原則に基づく実験計画と結果の解析で重要な統計学的方法が、分散を複数の成分（偶然の誤差や各要因の影響）の和としてモデル化し分析する分散分析の方法である。

品種・施肥量・圃場の3因子につき各3水準を設定するとしよう。一般には全部で 3 x 3 x 3 = 27 通りの実験が必要である。しかし、交互作用が無視できる場合には表2 に示すように9通りに減らすことができ、

![](https://upload.wikimedia.org/wikipedia/ja/thumb/2/2b/実験計画1.gif/220px-実験計画1.gif)
![](https://upload.wikimedia.org/wikipedia/ja/thumb/6/69/実験計画2.gif/220px-実験計画2.gif)

https://www.yodosha.co.jp/smart-lab-life/statics_pitfalls/statics_pitfalls10.html
著／三中信宏
第10回 実験計画はお早めに―完全無作為化法 （2018/01/19公開）

2017-02-05
https://www.placeon.jp/blog/words/words_monozukuri/experimental_design/
試験回数を減らそう（実験計画法）

2017-10-12
https://www.trifields.jp/r-cran-task-view-design-of-experiments-analysis-of-experimental-data-723
R言語 CRAN Task View：実験計画法（DoE）および実験データの分析の設計 | トライフィールズ

2011
https://www.jstage.jst.go.jp/article/weed/56/1/56_1_24/_article/-char/ja/
実験計画の立て方とRを用いた分散分析: 実験計画法に応じた分散分析の実行
https://www.jstage.jst.go.jp/article/weed/56/1/56_1_24/_pdf/-char/ja

2016年08月20日
https://www.asakura.co.jp/books/isbn/978-4-254-12216-9/
朝倉書店｜Rで学ぶ 実験計画法

2010/12/1
http://www.juse-p.co.jp/cgi-bin/html.pl5?i=ISBN978-4-8171-9371-1
ＲとＲコマンダーではじめる実験計画法
http://www.ec.kansai-u.ac.jp/user/arakit/RDOE.html
RDOE


2012/07/03
https://www.monodukuri.com/gihou/article/74
直交表の技法解説記事 主な直交表の種類と特徴 - ものづくり.com

https://kqerg.jimdo.com/ホーム/直交表/4水準系/
4水準系直交表 4 Levels Orthogonal Array - 関西品質工学研究会

### orthogonal array
直交表

2016-09-18
http://nakhirot.hatenablog.com/entry/20160918/1474166690
R 実験計画法を利用した要因分析 - DSL_statblog

2. 直交表によるパターン数の削減

Rのconjointパッケージに含まれるcaFactorialDesign関数を用いると直交表を作成した上でパターン数を削減することができる。

    install.packages("conjoint", dependencies=TRUE)
    library(conjoint)

Error : .onLoad failed in loadNamespace() for 'rgl', details:

2016/06/08
https://fisproject.jp/2016/06/design-of-experiment/
【R】実験計画法と分散分析【DoE.base】 | FiS Project

直交計画
Rでは {DoE.base} で直交表を生成できる。上記例だと, L9-3-4の直交表となる。

	require(DoE.base)
	table <- oa.design(nfactors = 4, nlevels = 3)
	table

分散分析

Sep 12, 2012
https://www.slideshare.net/itoyan110/r-14261638
Rで実験計画法 後編

Sep 5, 2011
https://www.slideshare.net/itoyan110/r-9139125
Rで実験計画法 前編

04/2011
http://www1.beuth-hochschule.de/FB_II/reports/Report-2011-004.pdf
Tutorial for designing experiments using the R package RcmdrPlugin.DoE


### Dummy
擬水準

http://www.ab.cyberhome.ne.jp/~t-nojima/RQE/ps12.html
ダミー（擬水準）法と多水準作成法

https://support.minitab.com/ja-jp/minitab/18/help-and-how-to/modeling-statistics/doe/supporting-topics/taguchi-designs/dummy-treatments-for-taguchi-designs/
タグチ計画のダミー処理 - Minitab
https://support.minitab.com/en-us/minitab/18/help-and-how-to/modeling-statistics/doe/supporting-topics/taguchi-designs/dummy-treatments-for-taguchi-designs/
Dummy treatments for Taguchi designs - Minitab

2012/07/04
https://www.monodukuri.com/gihou/article/75
直交表の技法解説記事 直交表で水準数が余る時、足りない時の対処法 - ものづくり.com
「ダミー法」

1994年
http://ebsa.ism.ac.jp/ebooks/node/581
農業実験計画法小史 | 電子図書システム
http://ebsa.ism.ac.jp/ebooks/sites/default/files/ebook/581/pdf/ch03-12.pdf
12. ４水準因子の L₃₂ 直交表へのわりつけ
擬水準


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
## meta-analysis
[メタアナリシス](https://ja.wikipedia.org/wiki/%E3%83%A1%E3%82%BF%E3%82%A2%E3%83%8A%E3%83%AA%E3%82%B7%E3%82%B9)

https://github.com/haruosuz/microbe/blob/master/references/README.microbiome.md#meta-analysis

----------
## multiple comparison
多重比較

https://tjo.hatenablog.com/entry/2018/06/12/093633
多重比較補正のはなし - 六本木で働くデータサイエンティストのブログ

http://www.statsbeginner.net/entry/2014/11/01/140721
検定の繰り返しと多重比較について（追記あり） - StatsBeginner: 初学者の統計学習ノート

http://takehiko-i-hayashi.hatenablog.com/entry/20110209/1297209825
無から有（意差）を生む：多重比較でウソをつく方法 - Take a Risk：林岳彦の研究メモ

----------
## distance
距離

https://ja.wikipedia.org/wiki/距離函数
計量（metric）
擬距離 (pseudometric) 
半距離 (semimetric) 

http://cse.naro.affrc.go.jp/minaka/R/R-cluster2.html
距離尺度

計量性（metricity）
計量（metric）

A3') 擬計量性（pseudometricity）：
擬計量（pseudometric）

三角不等式（A4）

クラスター分析や系統分析では，A4よりもさらに厳しい次の条件群の方がむしろ重要である：

A4') 相加性（additivity）：

A4'') 超計量性（ultrametricity）：

擬計量＜非計量＜計量の順に定義の厳しさが大きくなっていく．計量性・相加性・超計量性の間にも同じ関係がある：

https://en.wikipedia.org/wiki/UniFrac
This definition satisfies the requirements of a distance metric, being non-negative, zero only when entities are identical, transitive, and conformant to the triangle inequality.

https://www.ncbi.nlm.nih.gov/pubmed/20827291
ISME J. 2011 Feb;5(2):169-72. doi: 10.1038/ismej.2010.133. Epub 2010 Sep 9.
UniFrac: an effective distance metric for microbial community comparison.
Lozupone C1, Lladser ME, Knights D, Stombaugh J, Knight R.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3105689/
In this study, we present a mathematical proof that both weighted and unweighted UniFrac values have the formal requirements of a distance metric (Rudin, 1987): they are always non-negative, symmetric and satisfy the triangle inequality, and identical sequence sets have a value of 0 (Supplementary Methods). 


----------
## ordination
 PCA PCoA MDS

https://yokazaki.hatenablog.com/entry/2016/06/29/212153
RによるNMDSを用いた微生物群集構造解析 - yokaのblog
NMDS(non metric multidimensional scaling)
（Bray-Curtis指数による計算）

http://d.hatena.ne.jp/fronori/20140517
MDSとその愉快な仲間たち - 統計で迷子になる方法
1. 古典的（Classical）MDS：　別名、主座標分析（Principal Coordinate Analysis, PCoA, PCO）
PCoAは距離としてユークリッド距離を用いた場合は、主成分分析（PCA）と数学的に同等となる。
- 計量（Metric）MDS：　古典的MDSの上位集合（superset）。
- 非計量（Non-metric）MDS：　
- 一般化（Generalized）MDS：　

生態学ではbray-curtisなどを使うことがあるのが発見でした。

https://twitter.com/fronori/status/465902482246221824
Tetsuo Ishikawa on Twitter: "微生物生態学でPCAではなくPCoAを使うのはなぜ？ https://t.co/EWaIp917ko この論文 http://t.co/4aTfUB8Ulr がオススメ。多変量解析の手法の比較や違いの説明が詳しい。テーブル１の生態学の中でも分野による違いも興味深い。"
1:13 PM - 12 May 2014

http://hoxo-m.hatenablog.com/entry/20120313/p1
主座標分析について簡単に紹介するよ！ - ほくそ笑む
主成分分析との違いを簡単に言うと、主成分分析はユークリッド距離をなるべく保ちながら低次元に落とす方法ですが、主座標分析はユークリッド距離だけでなく、他の距離や類似度*2が使えるという点にあります。

### mds
### bray-curtis

https://en.wikipedia.org/wiki/Bray%E2%80%93Curtis_dissimilarity
Bray–Curtis and Jaccard indices are rank-order similar, but, Jaccard index is metric, and probably should be preferred instead of the default Bray-Curtis which is semimetric.[6]
http://cc.oulu.fi/~jarioksa/softhelp/vegan/html/vegdist.html

http://www.statgenet.med.kyoto-u.ac.jp/StatGenet/lectures/MyBook/Toukeiryou.pdf
統計量・スカラー・距離・測度・ 順序

ミンコフスキー距離では、p ≥ 1 の場合に距離関数であって、p < 1 の場合は三角不等
式を満たすとは限らないことがわかった。
p < 1 のミンコフスキー距離は半距離関数 (semimetric) と
呼ばれる。

https://sites.google.com/site/noteofpaediatricsurgery/24-machine-learning/xin-hao-fen-li/mds
多次元尺度法 - Draft of Pediatric Surgery

https://www1.doshisha.ac.jp/~mjin/R/Chap_27/27.html
Rと多次元尺度法

(2)　MDS関数
①　計量多次元尺度法の関数
　 Rのパッケージ stats には、計量多次元尺度法の関数 cmdscale （Classical (Metric) Multidimensional Scaling） がある。この古典的多次元尺度法は、主座標分析 (principal coordinate analysis) とも呼ばれている[2]。古典的多次元尺度法に用いる距離がユークリッド距離である場合は、相関行列を用いた主成分分析と等価である。

(2)　非計量多次元尺度法

2017-11
https://sites.google.com/view/cer-ecoplate/cer2017?authuser=0
微生物群集機能を評価するためのエコプレートの統計解析講座
https://sites.google.com/view/cer-ecoplate/講義資料ecoplate解析/ecoplate解析-3
CERエコプレート講座 - EcoPlate解析 (3)

Bray-Curtis距離

主座標分析(PCoA: Principal Coordinate Analysis)の基礎

この意味でPCoAは距離を維持した手法のため、計量的多次元尺度法(metric Multi-Dimensional Scaling: metric MDS）とも呼ばれます。計量性の呪縛を断ち切り、距離の違いを非類似度のランクに変換してから可視化する方法は非計量的多次元尺度法、non-metric MDS, NMDSとよばれていますが、ここでは時間の関係上説明しません。以下のウェブログの解説が詳しいです。
https://jonlefcheck.net/2012/10/24/nmds-tutorial-in-r/
NMDS Tutorial in R – sample(ECOLOGY)
ordicluster(example_NMDS,hclust(vegdist(community_matrix,"bray"))) 

2011
https://www.jstage.jst.go.jp/article/seitai/61/1/61_KJ00007176266/_pdf
生物群集解析のための類似度とその応用：
R を使った類似度の算出、グラフ化、検定
土居 秀幸 1
*†・岡村 寛 2†

Bray-Curtis指数

Bray-Curtis 指数はマンハッタン距離を標準化したもの
で、

特に Bray-Curtis 指数は、
後述する多次元尺度法の類似度として用いられることが
多い。

。非計量
多次元尺度の場合として、Bray-Curtis 指数を利用した結
果を図 3 に示す。

（Bray-Curtis 指数で定義された距離は、
ユークリッド距離と異なる特性を持つ semimetric と呼ば
れる距離になっている（Legendre and Legendre 1998））。

Bray-Curtis 指 数 に よ る NMDS

http://cse.fra.affrc.go.jp/okamura/program/vegan/
Bray-Curtis指数によるNMDS

http://www.yokoyamalab.org/societies/bsjspringseminar13/bsjseminar13_A2_27AM.pdf
フリーソフト「R」入門 はじめてのR
多次元尺度構成法
「MDSを使って使って使い倒す！
MDS入門から非対称MDS実習まで」
2010年3月27日～28日

計量MDSと非計量MDS(Rで実行するには…）

Torgerson (1952)の古典的MDSとGower (1966)の主座標分析の考え

http://www.mus-nh.city.osaka.jp/iso/argo/nl15/nl15-10-22.pdf
大垣俊一 Argonauta 15: 10 -22 (2008) 多様度と類似度、分類学的新指標

http://www.mus-nh.city.osaka.jp/iso/argo/nl01/nl01-15-26.html
大垣俊一 Argonauta 1: 15-26 (1999) 群集組成の多変量解析

----------
## [ROC](https://ja.wikipedia.org/wiki/受信者操作特性)

https://twitter.com/dariyasydykova/status/1063825681690370048
Dariya Sydykova on Twitter: "I made a new animation to demonstrate how an ROC curve relates to sensitivity and specificity for all possible cutoffs. The code and the gif file are available at https://t.co/uBjkUpHDr6 Again, thank you @ClausWilke for helping me with this one.… https://t.co/JGecyy0J1K"
11:06 AM - 17 Nov 2018

2017-05-27
https://qiita.com/kenmatsu4/items/550b38f4fa31e9af6f4f
【統計学】ROC曲線とは何か、アニメーションで理解する。

2016-02-21
https://oku.edu.mie-u.ac.jp/~okumura/stat/ROC.html
ROC曲線


----------
## statistical_significance

https://en.wikipedia.org/wiki/Statistical_significance

https://ja.wikipedia.org/wiki/有意
有意であるからといって「偶然ではない」と断定できるわけではなく、「偶然とは考えにくい」という意味に過ぎない。したがって、たとえば有意水準5%で有意という場合には、「実際には偶然に過ぎないのに、誤って『意味がある』と判断している」可能性が多くて5%ある。逆に、有意でないという場合には、あくまで「偶然かもしれない」という意味であって、「偶然である」とまでは断定できない。

https://twitter.com/TJO_datasci/status/1029746084896100357
TJO on Twitter: "どちらかと言うと例のツイートで僕が言いたかったのは「サンプルサイズ不足」の方を訝ることが多いということですね。「有意差なし」は帰無仮説を「棄却できない」のであって「採択する」わけではありませんので… "
11:06 AM - 15 Aug 2018

https://twitter.com/strnr/status/1024286159747342336
Stephen Turner on Twitter: "Using summary statistics to determine whether a non-significant result supports the absence of an effect https://t.co/SeuzU8atpt… https://t.co/Q8dapoaQh7"
9:30 AM - 31 Jul 2018
https://blog.usejournal.com/using-summary-statistics-to-determine-whether-a-non-significant-result-supports-the-absence-of-an-1ff61e97f7cf
By using both a frequentist and Bayesian approach, we can conclude that this non-significant result was probably not indicative of the absence of an effect. What’s more likely is that this non-significant result was due to the study being statistically underpowered.

https://twitter.com/koro485/status/1020335186913964032
KRSK on Twitter: "#一般人の方が時々誤解しておられること なにかの差を統計的に検定して、「統計的有意差が見られなかった」ときの解釈 (誤) 差がない (正) 差がないことを否定できない"
11:50 AM - 20 Jul 2018

2017年03月16日 
https://www.huffingtonpost.jp/nissei-kisokenkyujyo/null-hypothesis-statistics_b_15378064.html
ややこしいのが、帰無仮説に基づいて計算した確率が、有意水準以上であった場合だ。この場合は、帰無仮説は棄却されない。しかし、棄却されないからといって、帰無仮説が正しいと示された訳ではない。
帰無仮説は誤っているとも、正しいとも、示されなかったことになる。この場合、
「有意水準5%では、帰無仮説は棄却されず、誤っているとは言えない、と判断された。」
との結論となる。

http://team1mile.com/sjpr59-1/wp-content/uploads/2016/07/minaka.pdf
「ゆーい差決戦主義」（久保，2003, 2012）
古典的な仮説検定の方法論も時代によって変遷があった。たとえば，Fisher は対立仮説を設定せずに帰無仮説を検定しようとしたが，Neyman–Pearson は帰無仮説に対置する対立仮説を仮定したというちがいがある（Hacking, 1965；Barnett, 1999）。Neyman–Pearson の仮説検定の枠組みによれば，あるデータのもとで仮説検定を行ったとき，検定統計量が棄却域に入れば，帰無仮説を棄却するという意思決定を行う。

2012.09.04
https://www.yodosha.co.jp/jikkenigaku/statistics/q1.html
Q1 「統計学的に有意」とは何を意味しているのですか？｜バイオ実験に絶対使える統計の基本Q&A｜実験医学online：羊土社
統計的検定は論理学の背理法に相当し，仮説と観察のずれが有意であることをもって仮説を否定することを目的とするため，仮説が棄却された（有意である）場合と棄却されない（有意でない）場合では判断の強さが異なります．ある仮説が棄却された場合は反対の仮説が採択されますが，棄却されなかった場合は，それが何かの証明になるわけではなく，単に観察と仮説がとくに矛盾しないことが言えるだけで，その仮説が採択されるわけではありません．

----------
## sample

https://www.slideshare.net/takashijozaki1/tokyo-r140222-tjo
R初心者向け講座「Rによるやさしい統計学第20章『検定力分析によるサンプルサイズの決定』」20140222 TokyoR #36

8:30 PM - 17 Dec 2016
https://twitter.com/stattan/status/810296121805283328
統計たん@本質的に不良設定問題 on Twitter: "サンプルサイズはどれくらいなら十分ですか？！と聞かれても何を達成したいのかがわからないと答えられないですよ。例えば、とある効果量を仮定したもとで検定力を0.8にしたいとか、標準誤差の大きさを○○くらいに抑えたい、などなど。"

2015年9月4日
https://togetter.com/li/869445
統計解析の目的：知見の一般化？それとも、傾向の確認？その場合の再現性って何？ - Togetterまとめ 
- 推測統計学のもうひとつの問題は「実際にはほとんど誰もランダムサンプリングなどしていない」ということで，これは別に心理学や教育学，医学などよくそれで批判される分野に限ったことではなくて，推測統計学の本家本元である農学分野の研究でもランダム性などほとんど保証されないように見える。

https://ci.nii.ac.jp/naid/110007099999
実験・調査における「繰返し」と「反復」の誤用  [in Japanese]
Japanese Journal of Grassland Science 54(4), 348-351, 2009
例えば、1 haの牧草地を0.5 haずつの2プロットに分割し、それぞれのプロットに肥料処理（例えば、多肥と少肥）を行うとする。この時、それぞれの処理を行ったプロット内で、ランダムな場所に3ヶ所ずつの一定面積を選んで収量の測定を行う。これをもって3反復と考えた実験では、肥料処理の差異を統計的に判定することはできない。本報ではその理由を示し、どのような実験計画を組めば統計的に差異を検出できるかを示す。

### sample size

http://aoki2.si.gunma-u.ac.jp/lecture/mb-arc/arc042/10256.html
No.10256　独立した2群の差　サンプルサイズの偏り　　【初心者】　2009/07/04

サ ンプルサイズのアンバランスは，忌避すべきものではありません。実験計画を立てる段階では，サンプルサイズは揃える方がよいでしょう。その意味は，全体の サンプルサイズが決まっているなら，サンプルサイズを同数にした方が検出力が一番高いからです。しかし，データ収集後にデータ解析する段階で群を分けて比 較するような場合にはサンプルサイズが同じになることは期待薄でしょう。このようなときに，サンプルサイズをわざわざ減らすと，どのような減らしかたをし ようとも，たとえ同数にするにしても，検出力は下がるのです。

https://toukeigaku-jouhou.info/2017/12/14/samplesize-and-the-number-of-samples/
サンプルサイズとサンプル数の違い（標本の大きさと標本数）

2017年9月30日
https://sites.google.com/site/fishermultiplecomparison/samplesize
サンプル数とサンプルサイズ n は意味が違う - 統計学的手法の話題 - 生物科学研究所

http://interdisciplinary.hateblo.jp/entry/20130503/p1
標本の大きさ（サンプルサイズ）の意味でサンプル数を使うのは間違いである

http://daas.world.coocan.jp/toukei_hosoku/hyohon.htm
4.　標本数（サンプル数）と標本の大きさ（サンプルサイズ）

http://www2.kobe-u.ac.jp/~hamori/Jhamori/explanation(sample%20size).pdf
補足説明 (1)「標本の大きさ(サンプルサイズ:sample size)と標本数」について

### n=3

https://twitter.com/strnr/status/974402251375734784
Stephen Turner on Twitter: "“But I need n=3 please try the analysis anyway”… "

2017年10月2日
https://sites.google.com/site/fishermultiplecomparison/variance
標本分散と標本不偏分散，nで割るかn-1で割るか，不偏標準偏差の話題も含めて - 統計学的手法の話題 - 生物科学研究所

例えば，母平均は母集団分布の位置を表す母数だが，これは，最低限として（誤差は最大になるが），測定値１個からなる標本（n=1）で足りる。
n = 0 は駄目だが，n ≧ 1 ならば，「自由に」使える，のである。 それを分母で表現している。

一方，バラツキの母数である母分散は，一つの測定値では推定できない。
これが母分散を求めるときの自由度n-1 につながる。 n = 1 では不可（分母が0になる），n ≧ 2 ならば自由に使える，ということを分母で示している。

https://www.sbj.or.jp/sbj/sbj_tokei_kaiseki.html
生物工学会誌 –『間違いから学ぶ実践統計解析』 | 公益社団法人 日本生物工学会
第3回	データ数はいくつ必要	川瀬 雅也・松田 史生	(2016)
https://www.sbj.or.jp/wp-content/uploads/file/sbj/9408/9408_tokei_kaiseki.pdf
実験は 3 回繰り返さないと
実験は 3 回反復

Oct 30, 2010
https://www.youtube.com/watch?v=Hz1fyhVOjr4
Biologist talks to statistician - YouTube

2008/03/05
http://www.kenkyuu2.net/cgi-biotech2/biotechforum.cgi?mode=view;Code=787
BioTechnicalフォーラム [n=3のときの統計処理]

http://aoki2.si.gunma-u.ac.jp/lecture/mb-arc/arc043/12199.html
No.12199　標準偏差を求めるためのデータ数　　【古川】　2010/03/01(Mon) 00:12

「3 以上でなければならない」ことなどありません。サンプルサイズは2以上でよいのです。
だれが（どこで）「3 以上でなければならない」といっているのですか？

http://aoki2.si.gunma-u.ac.jp/lecture/mb-arc/arc041/05789.html
No.05789　n=2での標準偏差　　【佐々木】　2008/02/10(Sun) 00:20 

http://aoki2.si.gunma-u.ac.jp/lecture/mb-arc/arc040/02768.html
No.02768　n=2の場合の検定　　【suzuki】　2007/02/19(Mon) 12:51 

----------
## plot

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

### Simpson's paradox

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
## references

http://japanr.net
Japan.R
日本各地で統計処理ソフトウェアである R に関する勉強会が行われています。これらの勉強会の主催者や参加者が年に一度集まって開催されるイベントが Japan.R です。

http://leeswijzer.org/files/books.html
MINAKA Nobuhiros boeken
公刊書籍一覧（出版年順）
【著書】三中信宏『統計思考の世界：曼荼羅で読み解くデータ解析の基礎』2018年4月下旬刊行予定，技術評論社，東京 → 目次案

化学と生物 [統計検定を理解せずに使っている人のために](https://twitter.com/search?q=統計検定を理解せずに使っている人のために)
- http://doi.org/10.1271/kagakutoseibutsu.51.318
- http://doi.org/10.1271/kagakutoseibutsu.51.408
- http://doi.org/10.1271/kagakutoseibutsu.51.483

https://twitter.com/stattan/status/973732995927498752
統計たん@本質的に不良設定問題 on Twitter: "群馬大学の青木先生のページにパラメトリック検定とノンパラメトリック検定の手法対応・分類表があるわ。ノンパラメトリック検定は何を使ったらいいかわかりにくいから，必要になったら参照してみてね。https://t.co/1thUnNCYCv"

http://aoki2.si.gunma-u.ac.jp/lecture/Kentei/nonpara.html
パラメトリックな手法とノンパラメトリックな手法

http://ebsa.ism.ac.jp
統計科学のための電子図書システム

http://todo-ran.com/t/bestworst
都道府県ベスト＆ワースト｜都道府県別統計とランキングで見る県民性 [とどラン]

http://aoki2.si.gunma-u.ac.jp/taygeta/statistics.cgi
統計学関連なんでもあり

http://d.hatena.ne.jp/haruosuz/20051130
統計 - Haruo Suzuki / Bioinformatics

----------
## toukei-kentei

- https://twitter.com/toukei_kentei

http://www.toukei-kentei.jp
統計検定：Japan Statistical Society Certificate
次回の検定情報
2019年
6月16日(日)



個人申込：9月5日～10月12日

2018.08.30
https://kawazu-frog.com/統計検定２級と３級の差がすごすぎる。

2018年08月29日
https://qiita.com/tachiken0210/items/a5a2363b481896f04fa7
統計検定2級を１週間の勉強期間で合格するためにしたことまとめ

2018年04月18日
https://matome.naver.jp/odai/2147251580620745701
統計検定(2級・準1級)合格のための勉強法・参考書 - NAVER まとめ

http://www.medicalmed.press/entry/2018/02/25/221327
統計検定準1級に医学生が合格するためのオススメ参考書10選 - 医学生がRとPythonで医療統計

http://id.fnshr.info/2016/07/19/stat-cerf-j1q/
統計検定準1級を取るための勉強法｜Colorless Green Ideas
2018年2月23日追記：2017年7月27日に準1級の出題範囲が変更されている [3] 。

2018年02月19日
https://qiita.com/drken/items/089b8443305df047b44e
統計検定 1 級に合格する方法

http://wanko-sato.hatenablog.com/entry/2017/01/21/175305
【統計】統計検定準一級を受けようと思う。 - データ分析系男子。

2015/06/27 
http://blog.kentei-uketsuke.com/suzuki/archives/2771
統計検定準1級をとりあえず受験

----------
## link

- https://twitter.com/sugakubunka

https://twitter.com/stattan
統計たん@本質的に不良設定問題

https://twitter.com/tousuuken
統計数理研究所

http://www.ism.ac.jp/topevent_j/index.html
イベント一覧 | 統計数理研究所

----------
## people

## dr-kid


https://twitter.com/Dr_KID_/status/1094372164432621568
Dr. KID on Twitter: "DAGを使って因果関係、交絡、選択バイアスを見分ける方法について 今回は、DAGを使って ・因果関係 ・（偽りの）相関関係（交絡） ・逆の因果関係 ・選択バイアス を説明しました。名前を覚えるより、構造を理解した方が実践的です。 https://t.co/iG4cDxoFhK"
6:07 PM - 9 Feb 2019
 2019年2月10日
https://www.dr-kid.net/dag-cause-and-effect
DAGを使って因果関係、交絡、選択バイアスを見分ける方法について｜Dr.KIDの小児科クリニック

https://twitter.com/Dr_KID_/status/1094372164432621568
Dr. KID on Twitter: "DAGを使って因果関係、交絡、選択バイアスを見分ける方法について 今回は、DAGを使って ・因果関係 ・（偽りの）相関関係（交絡） ・逆の因果関係 ・選択バイアス を説明しました。名前を覚えるより、構造を理解した方が実践的です。 https://t.co/iG4cDxoFhK"
6:07 PM - 9 Feb 2019
 2019年2月10日
https://www.dr-kid.net/dag-cause-and-effect
DAGを使って因果関係、交絡、選択バイアスを見分ける方法について｜Dr.KIDの小児科クリニック

https://www.dr-kid.net/entry-2018-10-13-053403
【因果推論】交絡と交絡因子について【シンプソンのパラドックスの１例】｜Dr.KIDの小児科クリニック

https://twitter.com/Dr_KID_/status/1020488169005826048
Dr. KID on Twitter: "土曜は疫学について語ります。 今回はメタ解析の導入編です。 / “システマティック・レビューとメタ解析について①　〜イントロ編〜 - ドクター・キッド” https://t.co/gWAwsKCkOJ"
9:58 PM - 20 Jul 2018

https://twitter.com/Dr_KID_/status/1022981447416598528
Dr. KID on Twitter: "土曜日は疫学の日。 今回はシステマティックレビューとメタ解析において、どのように仮設をたて、文献検索をするのか、説明してみました。 論文をチェリーピッキングしないために、系統だって評価する必要があります。 https://t.co/9CoAHDceek"
7:05 PM - 27 Jul 2018

https://twitter.com/Dr_KID_/status/1025550141011374080
Dr. KID on Twitter: "土曜は疫学の記事を書いています。 先週の続きで、今回はメタ解析の異質性について解説しています。 異質性がある場合、異質性の元（effect modifier）を探る必要があります。 システマティック・レビューとメタ解析について③… https://t.co/SKfegyapoS"
9:13 PM - 3 Aug 2018

https://twitter.com/Dr_KID_/status/1028213379960197120
Dr. KID on Twitter: "土曜は疫学の日。 今回はメタ解析における異質性（Heterogeneity）の統計学的な評価方法について解説します（Cochran Q, I-squared）。 / “システマティック・レビューとメタ解析について④　〜異質性（H…” https://t.co/nx9qdi3qfG"
5:35 AM - 11 Aug 2018

https://twitter.com/Dr_KID_/status/1030595619046346752
Dr. KID on Twitter: "土曜は疫学の日。 メタ解析の原理について、シリーズ形式で解説してきています。 本日は、固定効果とランダム効果について、簡単に説明しました。 システマティック・レビューとメタ解析について⑤　〜固定効果とランダム効果〜 - ドクター… https://t.co/d0QpLnpiVW"
7:21 PM - 17 Aug 2018

https://twitter.com/Dr_KID_/status/1033154117194022912
Dr. KID on Twitter: "土曜は疫学の日です。今回は、メタ解析における ・お蔵入り問題 ・出版バイアスの評価方法（Funnel Plot） について、簡単に説明しています。 システマティック・レビューとメタ解析について⑥　〜出版バイアスの評価方法１（Fu… https://t.co/E3X7F4Gs7B"
8:48 PM - 24 Aug 2018

![](https://pbs.twimg.com/card_img/1025546807483359234/rC2iTTcK?format=jpg&name=600x314)

## leeswijzer
MINAKA Nobuhiro

https://twitter.com/leeswijzer

http://d.hatena.ne.jp/shorebird/20180610
書評　「統計思考の世界」 - shorebird　進化心理学中心の書評など

https://gihyo.jp/dp/ebook/2018/978-4-7741-9754-8
統計思考の世界 ～曼荼羅で読み解くデータ解析の基礎 | Gihyo Digital Publishing … 技術評論社の電子書籍
本書は，2018年5月18日に発売された書籍の電子版です。
EPUB/PDFセット

http://gihyo.jp/book/2018/978-4-7741-9753-1
統計思考の世界 ～曼荼羅で読み解くデータ解析の基礎：書籍案内｜技術評論社
目次
http://gihyo.jp/book/2018/978-4-7741-9753-1#toc
第11講　統計モデル選択論：統計学的アブダクションのために

https://note.mu/leeswijzer/n/ne827077ad556
姉妹本3冊を書き終えて｜leeswijzer｜note

http://www.agr.kyushu-u.ac.jp/lab/entomology/news-report_010.html
農業生物資源学特論第五（講師：三中信宏博士）の講義ビデオの公開
九州大学附属図書館付設 教材開発センター の撮影・編集によって三中先生の講義内容をビデオにて公開することができるようになりました。

KyushuUniv
農業生物資源学特論第五
 講　師：三中 信宏 先生（独立行政法人農業環境技術研究所）
 期　間：2014年2月3日～5日 

https://www.youtube.com/watch?v=0HfJpfJH-co&feature=youtu.be
4.生物統計学概論（1）：統計モデル選択と計算統計学（三中 信宏 先生） - YouTube
1:25:00

51:15 線形統計モデル（LM）への入り口

http://www.math.wm.edu/~leemis/chart/UDR/UDR.html
Univariate Distribution Relationship Chart

	#install.packages("TeachingDemos")
	library(TeachingDemos)
	clt.examp(1)
	clt.examp(2)

https://www.youtube.com/watch?v=if-OYPt08YI
11.形態測定学概論：サイズとシェイプの多変量統計学 （三中 信宏 先生）

----------
## yusuke_tsugawa
https://twitter.com/yusuke_tsugawa

https://twitter.com/hashtag/究極の食事

2018年5月18日
http://minato.sip21c.org/bookreview/evidence-based-diet.html
書評：津川友介『世界一シンプルで科学的に証明された究極の食事』東洋経済新報社

http://minato.sip21c.org/bulbul2/20180507.html
【第1828回】 GW明け初日から講義で，津川友介『世界一シンプルで科学的に証明された究極の食事』を勧めたが鵜呑みはせず批判的に読むことが大事（2018年5月7日）
http://minato.sip21c.org/bulbul2/20180506.html
牧田善二『医者が教える食事術　最強の教科書：20万人を診てわかった医学的に正しい食べ方68』
津川友介『世界一シンプルで科学的に証明された究極の食事』

2018-04
https://togetter.com/li/1222611
世界一シンプルで科学的に証明された究極の食事について - Togetter

https://i-voce.jp/feed/9567/
医学的に｢健康に良い食べ物｣は5つしかない【正しい健康情報の読み解き方】｜東洋経済オンライン

https://healthpolicyhealthecon.com/2018/03/22/the-best-diet/
「世界一シンプルで科学的に証明された究極の食事」 – 医療政策学×医療経済学

https://healthpolicyhealthecon.com/2017/12/02/causal-inference-book/
『「原因と結果」の経済学』の無料公開！ – 医療政策学×医療経済学

2017/9/25
http://medical.nikkeibp.co.jp/leaf/all/cadetto/tuusin/201709/552936.html
津川友介（UCLA医療政策学者）×山本雄士（ミナケア社長）
社会的インパクトのある研究テーマの見つけ方

2018.03.29
http://college.nikkei.co.jp/article/112272017.html
人生を経済学で考えよう（14）　小テストを行うなら、授業の前か後か｜慶應大学 中室牧子ゼミ｜日経カレッジカフェ | 大学生のためのキャリア支援メディア

----------
## tmaita77
舞田敏彦

1月8日
https://togetter.com/li/1187992
【舞田敏彦】舞田敏彦のデマに気がついた500人の人たち - Togetter

2017年4月23日
https://togetter.com/li/1103576
エクセル統計学者・舞田敏彦の光と影 - Togetter

https://twitter.com/demadayo88
【舞田敏彦】舞田敏彦さんにブロックされても頑張るグループ (@demadayo88) | Twitter

https://twitter.com/tmaita77
舞田敏彦 (@tmaita77) | Twitter

----------






