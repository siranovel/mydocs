smple_diff_test
---------------
2群の母平均の差の検定

* 使い方

パラメトリック検定の場合

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
hypothTest2 = Num4HypothTestLib::TwoSideTestLib.new
paraTest2 = Num4DiffTestLib::ParametrixTestLib.new(hypothTest2)
paraTest2.smple_diff_test(xi1, xi2, 0.05)
=> false
```

ノンパラメトリック検定の場合

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
hypothTest2 = Num4HypothTestLib::TwoSideTestLib.new
nonParaTest = Num4DiffTestLib::NonParametrixTestLib.new(hypothTest2)
nonParaTest.smple_diff_test(xi1, xi2, 0.05)
=> false
```

