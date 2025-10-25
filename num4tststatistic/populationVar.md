populationVar
=============
正規母集団の母分散の検定量を計算

## 統計的検定
### 検定の手順2

標本{x1 x2 ... xn}による母分散の検定統計量を計算する  
ただし、自由度n-1の階２乗分布に従う  
(num4hypothtstを使用して棄却域に入っているかどうか判定する)

## 使い方

```ruby
xi = xi = [35.2, 34.5, 34.9, 35.2, 34.8, 35.1, 34.9, 35.2, 34.9, 34.8]
sd = 0.4
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.populationVar(xi, sd*sd)
```

