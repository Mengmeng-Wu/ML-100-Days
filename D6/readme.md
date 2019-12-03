### Day 6 - outlier(例外值)處理

![](https://i.imgur.com/cyF2QAG.png)
![](https://i.imgur.com/6ml01ak.png)
![](https://i.imgur.com/KbkWmQX.png)


(圖片來源:第一屆機器學習百日馬拉松官網提供)

-----

<b>流程:</b>
篩選數值欄位 -> 繪製箱型圖(python:.boxplot())可以看數據坐落於那裡 -> 將NaN濾掉(python:.dropna()) -> 繪製 Empirical Cumulative Density Plot (ECDF)

* 直方圖繪製和ECPDF繪製較適用於一維數據
* 經驗累績分佈函數(empirical cumulative distribution function,ECPDF)是累積分佈函數(cumulative distribution function,CDF)的一個估測
* 在ECDF的定義中，每個資料點的機率和質量相同，若該資料點重複，此點的機率質量就會累加。
* 
ECDF介紹(但不太詳細) [探索資料-ECDF](https://medium.com/ai%E5%8F%8D%E6%96%97%E5%9F%8E/exploratory-data-analysis-%E6%8E%A2%E7%B4%A2%E8%B3%87%E6%96%99-ecdf-7fa350c32897)
