independency
============
独立性の検定

* 使い方

```ruby
fij = [
  [57, 33, 46, 14],
  [89, 24, 75, 12],
]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.independency(fij, 0.05)
```

