pearsoCorrelation
=================
ピアソン相関係数

## 使い方
### 無相関の検定の場合

```ruby
x = [113, 64, 16, 45, 28, 19, 30, 82, 76]
y = [31, 5, 2, 17, 18, 2, 9, 25, 13]
corrTest = CorrTestLib::DecorrTestLib.new
corrTest.pearsoCorrelation(x, y, 0.05)
```

### 母相関係数の検定の場合

```ruby
x = [113, 64, 16, 45, 28, 19, 30, 82, 76]
y = [31, 5, 2, 17, 18, 2, 9, 25, 13]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
corrTest = CorrTestLib::CorreFactLib.new(hypothTest)
corrTest.pearsoCorrelation(x, y,  -0.3, 0.05)
```

### 差の母相関係数の検定の場合

```ruby
xy1 = [
        [113, 64, 16, 45, 28, 19, 30, 82, 76],
        [31, 5, 2, 17, 18, 2, 9, 25, 13]
      ]
xy2 = [
        [113, 64, 16, 45, 28, 19, 30, 82, 76],
        [31, 5, 2, 17, 18, 2, 9, 25, 13]
      ]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
corrTest = CorrTestLib::DiffCorreFactLib.new(hypothTest)
corrTest.pearsoCorrelation(xy1, xy2, 0.05)
```



