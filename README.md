# BondYieldSurface

## 債券殖利率描述
債券市場中，殖利率（yield）是一個觀察債券價格趨勢的指標，但又知道債券有不同到期期間（maturity），因此會使用橫軸為日期，縱軸為殖利率，內容則是不同到期期間的債券類型，如

![殖利率曲線](https://github.com/MinKuanIsHere/BondYieldSurface/blob/main/us_yield_curve.png)

但為了想要看出殖利率和到期債券在各時間點下的變化，此時就有殖利率期限結構（term structure）。x軸為日期、y軸為債券到期期間、z軸為殖利率，如

![殖利率期限結構](https://github.com/MinKuanIsHere/BondYieldSurface/blob/main/us_yield_surface.png)

## 檔案說明

|檔名|描述|
|-----|-----|
|us_2year.csv|美國2年期公債|
|us_5year.csv|美國5年期公債|
|us_10year.csv|美國10年期公債|
|us_20year.csv|美國20年期公債|
|us_30year.csv|美國30年期公債|
|yield_curve.ipynb|繪製殖利率曲線和期限結構的程式碼|
資料來源為嘉實資訊。
