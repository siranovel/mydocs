populationCorre
---------------
母相関係数の検定

## 使い方
### 両側検定の場合

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
hypothTest.populationCorre(-0.76655, 12, -0.3, a)
```

### 片側(右側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::RightSideTestLib.new
hypothTest.populationCorre(-0.76655, 12, -0.3, a)
```

### 片側(左側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::LeftSideTestLib.new
hypothTest.populationCorre(-0.76655, 12, -0.3, a)
```

