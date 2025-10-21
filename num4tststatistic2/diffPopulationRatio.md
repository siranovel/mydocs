diffPopulationRatio
===================
2つの母比率の差の検定

## 統計的検定
### 検定の手順1

(1) 両側検定  
　・帰無仮設：標本比率1 - 標本比率2 ＝ 0  
　・対立仮説：標本比率1 - 標本比率2 ≠ 0  
(2) 片側検定  
　・帰無仮設：標本比率1 - 標本比率2 ＝ 0  
　・対立仮説：標本比率1 - 標本比率2 ＜ 0  
(3) 片側検定  
　・帰無仮設：標本比率1 - 標本比率2 ＝ 0  
　・対立仮説：標本比率1 - 標本比率2 ＞ 0  

### 検定の手順2、検定の手順3

検定統計量を計算し、棄却域に入っているかどうか調べる  
棄却域に入っている場合、帰無仮設は棄てる

## 使い方

```ruby
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.diffPopulationRatio(469, 1200, 308, 900, 0.05)
```

