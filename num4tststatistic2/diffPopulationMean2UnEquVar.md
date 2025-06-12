diffPopulationMean2UnEquVar
===========================
2つの母平均の差の検定(不等分散性を仮定)

* 使い方

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.diffPopulationMean2UnEquVar(xi1, xi2, 0.05)
```

