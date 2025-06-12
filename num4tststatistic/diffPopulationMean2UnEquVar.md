diffPopulationMean2UnEquVar
===========================
2つの母平均の差の検定量(不等分散性を仮定)

* 使い方

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.diffPopulationMean2UnEquVar(xi1, xi2)
```

