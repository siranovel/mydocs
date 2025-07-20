fidelity
========
適合度の検定

## 使い方

```ruby
fi = [57, 33, 46, 14]
pi = [0.4, 0.2, 0.3, 0.1]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.fidelity(fi, pi, 0.05)
```

