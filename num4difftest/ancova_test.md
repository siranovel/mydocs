ancova_test
-----------
共分散分析

## 概要

回帰直線の平行性検定をする  
　平行であるならば、3群以上の母平均の差の検定(1元配置)  
回帰直線の有意性検定をする  
　有意性がない場合：3群以上の母平均の差の検定(1元配置)  
水準間の差の検定をする

## 使い方

```ruby
yi = [
    [3, 5, 3],
    [3, 3, 8],
    [2, 2, 2],
    [3, 4, 2],
    [1, 2, 0],
]
xi = [
   [35, 38, 39],
   [36, 39, 54],
   [40, 45, 39],
   [47, 52, 48],
   [64, 80, 70],
]
hypothTest2 = Num4HypothTestLib::TwoSideTestLib.new
paraTest2 = Num4DiffTestLib::ParametrixTestLib.new(hypothTest2)
paraTest2.ancova_test(yi, xi, 0.05)
=> true
```

