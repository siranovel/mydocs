df4welch
========
ウェルチ検定の為の自由度

## 概要

2つの母平均の差の検定(不等分散性を仮定)の為の自由度を計算する

## 使い方

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.df4welch(xi1, xi2)
```

