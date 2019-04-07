# statistics.correlation

**Table of Contents**
- [featuring](#featuring)
- [updates](#updates)
[2019](#2019)
[2018](#2018)
[2017](#2017)
[2016](#2016)
- [correlation](#correlation)

----------
## featuring

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

----------
## updates

### 2019

### 2018

### 2017

https://twitter.com/fronori/status/927889710206263301
Tetsuo Ishikawa on Twitter: "Rでの同順位ありスピアマン順位相関ρのp値の計算法について書きました。"Cannot compute exact p-value with ties"とか「タイがあるため、正確なp値を計算することができません」表示に怯まないために。 https://t.co/fj9aa3rw5F"
8:25 AM - 7 Nov 2017

https://twitter.com/kohske/status/930869204911194112
思い出した、シンプソンのパラドックスだ。 https://togetter.com/li/1014449
1:44 PM - 15 Nov 2017

https://togetter.com/li/1014449
生態学的誤謬とシンプソンのパラドックス - Togetter
2016年8月20日
![](https://pbs.twimg.com/media/CqQfKiAUAAAdI4D.png:small)

https://twitter.com/h_okumura/status/930651352052715521
労働時間と知的好奇心には，国レベルでは非常に強い負の相関があるが，個人レベルでは逆に正の相関がある https://oku.edu.mie-u.ac.jp/~okumura/stat/piaac.html
11:19 PM - 14 Nov 2017
https://oku.edu.mie-u.ac.jp/~okumura/stat/piaac.html
PIAACデータ解析
労働時間と知的好奇心に強い負の相関があるというツイートがあり，それに対して疑問の声があった。

	#cat prg*.csv > all.csv
	library(data.table)
	data = fread("all.csv")
	object.size(data)
	dim(data)

	wh = as.numeric(data$D_Q10)  # 週あたり仕事時間
	ll = as.numeric(data$I_Q04d) # 新しいことを学ぶのが好き
	boxplot(wh ~ ll)

	cor.test(wh, ll)

	cntry = as.numeric(data$CNTRYID)
	boxplot(wh[cntry==392] ~ ll[cntry==392])
	cor.test(wh[cntry==392], ll[cntry==392])

	summary(lm(ll ~ wh + factor(cntry)))
    # wh                0.001243   0.000180   6.904 5.08e-12 ***

	whc = tapply(wh, factor(cntry), function(x)mean(x,na.rm=TRUE))
	llc = tapply(ll, factor(cntry), function(x)mean(x,na.rm=TRUE))
	plot(whc, llc)
	cor.test(whc, llc)

結論：国レベルでは，労働時間が増えるほど知的好奇心は減る。個人レベルでは，労働時間が増えるほど知的好奇心は増える。

要するにSimpsonのパラドックスである。国レベルと個人レベルの混同はEcological Fallacy（生態学的誤謬）とも呼ばれる。地域の大人に勉強を教えてもらうと成績が下がる？も参照。

奥村 晴彦
Last modified: 2019-03-17 13:07:49


### 2016

----------
## 


