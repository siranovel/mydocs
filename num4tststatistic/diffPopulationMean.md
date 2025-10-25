diffPopulationMean
==================
対応のある2つの母平均の差の検定量

## 統計的検定
### 検定の手順2

２つの標本の数が同じの場合の母平均の差の検定統計量を計算する  
ただし、自由度N-1のt分布に従う
(num4hypothtstを使用して棄却域に入っているかどうか判定する)

## 使い方

```ruby
xi1 = [37.1, 36.2, 36.6, 37.4, 36.8, 36.7, 36.9, 37.4, 36.6, 36.7]
xi2 = [36.8, 36.6, 36.5, 37.0, 36.0, 36.5, 36.6, 37.1, 36.4, 36.7]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.diffPopulationMean(xi1, xi2)
```

