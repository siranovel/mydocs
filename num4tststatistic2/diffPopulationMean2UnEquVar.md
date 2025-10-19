diffPopulationMean2UnEquVar
===========================
2つの母平均の差の検定(不等分散性を仮定)

## 統計的検定
### 検定の手順1

(1) 両側検定  
　・帰無仮設：標本平均1＝標本平均2  
　・対立仮説：標本平均1≠標本平均2  
(2) 片側検定
　・帰無仮設：標本平均1＝標本平均2  
　・対立仮説：標本平均1＜標本平均2  
(3) 片側検定
　・帰無仮設：標本平均1＝標本平均2  
　・対立仮説：標本平均1＞標本平均2  

### 検定の手順2、検定の手順3

検定統計量を計算し、棄却域に入っているかどうか調べる  
棄却域に入っている場合、帰無仮設は棄てる

## 使い方

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.diffPopulationMean2UnEquVar(xi1, xi2, 0.05)
```

