populationVar
=============
正規母集団の母分散の検定

## 統計的検定
### 検定の手順1

(1) 両側検定  
　・帰無仮設：平均＝母分散  
　・対立仮説：平均≠母分散  
(2) 片側検定
　・帰無仮設：平均＝母分散  
　・対立仮説：平均＜母分散  
(3) 片側検定
　・帰無仮設：平均＝母分散  
　・対立仮説：平均＞母分散  

### 検定の手順2、検定の手順3

検定統計量を計算し、棄却域に入っているかどうか調べる  
棄却域に入っている場合、帰無仮設は棄てる

## 使い方

```ruby
xi = [35.2, 34.5, 34.9, 35.2, 34.8, 35.1, 34.9, 35.2, 34.9, 34.8]
sd = 0.4
hypothTest = Num4HypothTestLib::LeftSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.populationVar(xi, sd*sd, 0.05)
```

