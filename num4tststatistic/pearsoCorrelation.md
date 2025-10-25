pearsoCorrelation
=================
ピアソン相関係数を計算する

## 概要

2変数の間の直線的関連の程度を表す係数を計算する  
(num4hypothtstを使用して無相関、母相関の検定統計量を計算し、棄却域に入っているかどうか判定する)  

## 使い方

```ruby
x = [113, 64, 16, 45, 28, 19, 30, 82, 76]
y = [31, 5, 2, 17, 18, 2, 9, 25, 13]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.pearsoCorrelation(x, y)
```
