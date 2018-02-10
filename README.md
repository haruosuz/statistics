Haruo Suzuki (haruo[at]g-language[dot]org)  
Last Update: 2018-02-10

----------

# Statistics
**統計学**

## Table of Contents
- [Updates](#updates)
  - [2018-01](#2018-01)
- [multiple comparison](#multiple-comparison)
- [batch effect](#batch-effect)
- [sample](#sample)
  - [sample size](#sample-size)
  - [n=3](#n3)
- [Causal inference](#causal-inference)
- [References](#references)
  - [Colorless Green Ideas](#colorless-green-ideas)

----------
## Updates

----------
### 2018

http://www.ism.ac.jp/events/2018/meeting0213_14.html
小研究会「生態学における統計教育：計算より概念と考え方」
日時 2018年2月13日(火) 13:00～ 14日(水)12:00
場所 統計数理研究所 3階 第2セミナー室

----------
### 2017

----------
### 2016

http://team1mile.com/sjpr59-1/contents_comment/minaka2016/
三中(2016) | 特集「心理学の再現可能性：我々はどこから来たのか　我々は何者か　我々はどこへ行くのか」
三中信宏
統計学の現場は一枚岩ではない
http://team1mile.com/sjpr59-1/wp-content/uploads/2016/07/minaka.pdf

----------

### 2017-12

第11回 正規分布を踏まえたパラメトリック統計学の降臨 （2017/01/26公開）

https://www.yodosha.co.jp/smart-lab-life/statics_pitfalls/statics_pitfalls10.html
第10回 実験計画はお早めに―完全無作為化法 - 統計の落とし穴と蜘蛛の糸 - Smart Lab Life - 羊土社

第1回 データ解析の第一歩は計算ではない （2017/11/10公開）

### 2017-05
http://d.hatena.ne.jp/R-statistiker/20170531/1496220635
2017-05-31 アメリカ統計学会「p値」声明文翻訳公開
■[情]「統計的有意性とP値に関するASA声明」

----------
### multiple comparison
多重比較

http://www.statsbeginner.net/entry/2014/11/01/140721
検定の繰り返しと多重比較について（追記あり） - StatsBeginner: 初学者の統計学習ノート

http://takehiko-i-hayashi.hatenablog.com/entry/20110209/1297209825
無から有（意差）を生む：多重比較でウソをつく方法 - Take a Risk：林岳彦の研究メモ

----------
### batch effect

(Oct. 2016)
http://bukai.pharm.or.jp/bukai_kozo/SARNews/SARNews_31.pdf
構造活性相関部会・ニュースレター <1 October, 2016>
植物におけるオミックス統合ネットワークシステム生物学 理化学研究所 福島敦史
非生物学的な(意味のない!)共発現関係が生 じる原因のいくつかは、RNA の品質や batch effect に帰する。batch effect とは、サンプルを得 る時期が異なった場合や別の研究室で行われた場合に、データ取得の際に発生する実験品質の 違いがオミックスデータに生じることを指す(特に大規模な実験では、不可避な変動である)。 通常、これらバイアスの推定と影響の緩和は、実験デザインに基づいた線形モデルによって行 うことができ、重要視されるようになっている。実際、我々も 50 種のシロイヌナズナ変異体 のメタボロームデータ解析の際には、このような batch effect を考慮した [11]。

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

Oct 30, 2010
https://www.youtube.com/watch?v=Hz1fyhVOjr4
Biologist talks to statistician - YouTube

https://ci.nii.ac.jp/naid/110007099999
実験・調査における「繰返し」と「反復」の誤用  [in Japanese]
Japanese Journal of Grassland Science 54(4), 348-351, 2009
例えば、1 haの牧草地を0.5 haずつの2プロットに分割し、それぞれのプロットに肥料処理（例えば、多肥と少肥）を行うとする。この時、それぞれの処理を行ったプロット内で、ランダムな場所に3ヶ所ずつの一定面積を選んで収量の測定を行う。これをもって3反復と考えた実験では、肥料処理の差異を統計的に判定することはできない。本報ではその理由を示し、どのような実験計画を組めば統計的に差異を検出できるかを示す。

### sample size
http://aoki2.si.gunma-u.ac.jp/lecture/mb-arc/arc042/10256.html
No.10256　独立した2群の差　サンプルサイズの偏り　　【初心者】　2009/07/04

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

https://www.sbj.or.jp/sbj/sbj_tokei_kaiseki.html
生物工学会誌 –『間違いから学ぶ実践統計解析』 | 公益社団法人 日本生物工学会
第3回	データ数はいくつ必要	川瀬 雅也・松田 史生	(2016)
https://www.sbj.or.jp/wp-content/uploads/file/sbj/9408/9408_tokei_kaiseki.pdf
実験は 3 回繰り返さないと
実験は 3 回反復

2008/03/05
http://www.kenkyuu2.net/cgi-biotech2/biotechforum.cgi?mode=view;Code=787
BioTechnicalフォーラム [n=3のときの統計処理]

----------
## CI
Confidence interval
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
## Causal inference
**因果推論**

https://sites.google.com/site/sshimizu06/home/presentations
[94] 清水昌平 (2018年2月28日-3月2日)  因果探索入門. xx, 滋賀.

http://kamonohashiperry.com/archives/531
統計的因果推論に関するスライドとRのサンプルコード | かものはしの分析ブログ

http://tjo.hatenablog.com/archive/category/統計的因果推論
統計的因果推論 カテゴリーの記事一覧 - 六本木で働くデータサイエンティストのブログ

2017-12-30
http://krsk-phs.hatenablog.com/entry/pure_criticism
炭水化物は体に悪い？脂質をたくさん摂るほど健康に良い？：2017年世界一に選ばれた科学論文を解説 - Unboundedly

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
## References

### Unclassified

http://aoki2.si.gunma-u.ac.jp/taygeta/statistics.cgi
統計学関連なんでもあり

----------
### [Colorless Green Ideas](http://id.fnshr.info)

http://www.keisoshobo.co.jp/book/b272873.html
ダメな統計学 - 株式会社　勁草書房

![](http://www.keisoshobo.co.jp//images/book/272873.jpg)

http://id.fnshr.info/2014/12/28/stats-done-wrong-ja-pdf/
『ダメな統計学』冊子PDFの公開｜Colorless Green Ideas

http://id.fnshr.info/2014/12/17/stats-done-wrong-toc/
ダメな統計学：目次｜Colorless Green Ideas

http://id.fnshr.info/2014/12/17/stats-done-wrong-13/
【翻訳】ダメな統計学 (13) 終わりに｜Colorless Green Ideas

実験が終わった後に統計学者に相談することは、しばしば単に検死を頼むようなものになる。統計学者は、何のせいで実験が死んだのかについて言うことができるかもしれない。

p値を普及させた人、R. A.フィッシャー [3]
![](http://id.fnshr.info/wp-content/uploads/sites/2/2014/12/r-a-fischer.jpg)


----------
### BDS

http://apprize.info/data/bioinformatics/1.html
How to Learn Bioinformatics - Ideology: Data Skills for Robust and Reproducible Bioinformatics - Bioinformatics Data Skills (2015)

Pay Attention to Experimental Design

To consult the statistician after an experiment is finished is often merely to ask him to conduct a post mortem examination. He can perhaps say what the experiment died of.

R.A. Fisher

https://github.com/haruosuz/books/tree/master/bds#pay-attention-to-experimental-design

----------
