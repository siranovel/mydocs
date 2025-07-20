populationMean
==============
正規母集団の母平均の検定

## 使い方

```ruby
xi = [15.5, 15.7, 15.4, 15.4, 15.6, 15.4, 15.6, 15.5, 15.4]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.populationMean(xi, 15.4, 0.05)
```

