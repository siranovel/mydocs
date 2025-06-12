utest
=====
マン・ホイットニーのU検定

* 使い方

```ruby
x = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
y = [180, 180, 235, 270, 240, 285, 164, 152]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
nonParaTest = Num4TstStatistic2Lib::NonParametrixTestLib.new(hypothTest)
nonParaTest.utest(x, y, 0.05)
```

