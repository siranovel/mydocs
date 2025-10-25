populationMean
==============
正規母集団の母平均の検定量を計算

## 統計的検定
### 検定の手順2

標本{x1 x2 ... xn}による母平均の検定統計量を計算する  
ただし、自由度n-1のt分布に従う  
(num4hypothtstを使用して棄却域に入っているかどうか判定する)

## 使い方

```ruby
xi = [15.5, 15.7, 15.4, 15.4, 15.6, 15.4, 15.6, 15.5, 15.4]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.populationMean(xi, 15.4)
```

