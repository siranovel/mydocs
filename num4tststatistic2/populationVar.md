populationVar
=============
正規母集団の母分散の検定

## 使い方

```ruby
xi = [35.2, 34.5, 34.9, 35.2, 34.8, 35.1, 34.9, 35.2, 34.9, 34.8]
sd = 0.4
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.populationVar(xi, sd*sd, 0.05)
```

