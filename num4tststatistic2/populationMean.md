populationMean
==============
正規母集団の母平均の検定

## 統計的検定
### 検定の手順1

(1) 両側検定  
　・帰無仮設：平均＝母平均  
　・対立仮説：平均≠母平均  
(2) 片側検定
　・帰無仮設：平均＝母平均  
　・対立仮説：平均＜母平均  
(3) 片側検定
　・帰無仮設：平均＝母平均  
　・対立仮説：平均＞母平均  

### 検定の手順2、検定の手順3

検定統計量を計算し、棄却域に入っているかどうか調べる  
棄却域に入っている場合、帰無仮設は棄てる

## 使い方

```ruby
xi = [15.5, 15.7, 15.4, 15.4, 15.6, 15.4, 15.6, 15.5, 15.4]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.populationMean(xi, 15.4, 0.05)
```

