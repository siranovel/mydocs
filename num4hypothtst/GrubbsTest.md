GrubbsTest
----------
グラブス・スミルノフの外れ値の検定

* 使い方

両側検定の場合

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::GrubbsTestLib.new
hypothTest.twoSideTest(2.3724, 8, a)
```

片側検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::GrubbsTestLib.new
hypothTest.oneSideTest(2.3724, 8, a)
```

