tDistTest
---------
T検定

* 使い方

両側検定の場合

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
hypothTest.tDistTest(2.683, 8, a)
```

片側(右側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::RightSideTestLib.new
hypothTest.tDistTest(1.6154, 5, a)
```

片側(左側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::LeftSideTestLib.new
hypothTest.tDistTest(-1.765, 18, a)
```

