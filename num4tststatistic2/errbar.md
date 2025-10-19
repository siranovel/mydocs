errbar
======
エラーバー出力

## 概要

繰り返しのあるデータから平均値を計算し、棒グラフとして描く。  

## 使い方

```ruby
xi = [3.4, 3.5, 3.3, 2.2, 3.3, 3.4, 3.6, 3.2]
outlier = Num4TstStatistic2Lib::OutlierLib.new
outlier.errbar("LDH", xi)
```

