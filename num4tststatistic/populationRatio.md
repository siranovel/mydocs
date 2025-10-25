populationRatio
===============
母比率の検定量を計算

## 統計的検定
### 検定の手順2

データ数Nの標本の標本比率m/Nの母比率の検定統計量を計算する  
ただし、標準正規分布に従う  
(num4hypothtstを使用して棄却域に入っているかどうか判定する)

## 使い方

```ruby
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.populationRatio(29, 346, 0.12)
```
