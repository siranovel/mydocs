diffPopulationVar
=================
2つの母分散の差の検定量を計算

## 統計的検定
### 検定の手順2

2つの標本{x11 x12 ... x1N1] {x21 x22 ... x2N2}による２つの母分散の差の検定統計量を計算する  
ただし、自由度(n1-1, N2-1)の分布に従う
(num4hypothtstを使用して棄却域に入っているかどうか判定する)

## 使い方

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.diffPopulationVar(xi1, xi2)
```

