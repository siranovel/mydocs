fDistTest
---------
F検定

## 使い方
### 両側検定の場合

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
hypothTest.fDistTest(0.4727, 11, 7, a)
```

### 片側(右側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::RightSideTestLib.new
hypothTest.fDistTest(0.4727, 11, 7, a)
```

### 片側(左側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::LeftSideTestLib.new
                      hypothTest.fDistTest(0.4727, 11, 7, a)
```

