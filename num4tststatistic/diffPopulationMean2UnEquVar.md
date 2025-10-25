diffPopulationMean2UnEquVar
===========================
2つの母平均の差の検定量(不等分散性を仮定)

## 統計的検定
### 検定の手順2

2つの標本{x11 x12 ... x1N1] {x21 x22 ... x2N2}による２つの母平均の差の検定統計量を計算する  
ただし、自由度mのt分布に従う  
自由度mは、ウェルチ検定の為の自由度で求めた値  
(num4hypothtstを使用して棄却域に入っているかどうか判定する)

## 使い方

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.diffPopulationMean2UnEquVar(xi1, xi2)
```

