normDistTest
------------
標準正規分布検定

## 使い方
### 両側検定の場合

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
hypothTest.normDistTest(-2.072, a)
```

### 片側(右側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::RightSideTestLib.new
hypothTest.normDistTest(-2.072, a)
```

### 片側(左側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::LeftSideTestLib.new
hypothTest.normDistTest(-2.072, a)
```

