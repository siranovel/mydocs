ks2test
=======
コルモゴルフ・スミルノフ検定(2標本)

## 使い方

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
nonParaTest = Num4TstStatistic2Lib::NonParametrixTestLib.new(hypothTest)
nonParaTest.ks2test(xi1, xi2, 0.05)
```

