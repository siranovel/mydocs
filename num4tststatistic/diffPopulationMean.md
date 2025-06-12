diffPopulationMean
==================
対応のある2つの母平均の差の検定量

* 使い方

```ruby
xi1 = [37.1, 36.2, 36.6, 37.4, 36.8, 36.7, 36.9, 37.4, 36.6, 36.7]
xi2 = [36.8, 36.6, 36.5, 37.0, 36.0, 36.5, 36.6, 37.1, 36.4, 36.7]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.diffPopulationMean(xi1, xi2)
```

