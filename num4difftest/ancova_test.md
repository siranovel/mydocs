ancova_test
-----------
共分散分析

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

