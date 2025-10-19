populationRatio
===============
母比率の検定

## 統計的検定
### 検定の手順1

(1) 両側検定  
　・帰無仮設：平均＝母比率  
　・対立仮説：平均≠母比率  
(2) 片側検定
　・帰無仮設：平均＝母比率  
　・対立仮説：平均＜母比率  

### 検定の手順2、検定の手順3

検定統計量を計算し、棄却域に入っているかどうか調べる  
棄却域に入っている場合、帰無仮設は棄てる

## 使い方

```ruby
hypothTest = Num4HypothTestLib::LeftSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.populationRatio(29, 346, 0.12, 0.05)
```

