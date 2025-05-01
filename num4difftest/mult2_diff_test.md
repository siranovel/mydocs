mult2_diff_test
---------------
3群以上の母平均の差の検定(2元配置)

* 使い方

パラメトリック検定の場合

```ruby
xij = [
         [
           [13.2, 15.7, 11.9],
           [16.1, 15.7, 15.1],
           [9.1,  10.3,  8.2],
         ],
         [
           [22.8, 25.7, 18.5],
           [24.5, 21.2, 24.2],
           [11.9, 14.3, 13.7],
         ],
         [
           [21.8, 26.3, 32.1],
           [26.9, 31.3, 28.3],
           [15.1, 13.6, 16.2],
         ],
         [
           [25.7, 28.8, 29.5],
           [30.1, 33.8, 29.6],
           [15.2, 17.3, 14.8],
         ],
]
hypothTest2 = Num4HypothTestLib::TwoSideTestLib.new
paraTest2 = Num4DiffTestLib::ParametrixTestLib.new(hypothTest2)
paraTest2.mult2_diff_test(xij, 0.05)
=>
  [true, true]
```

ノンパラメトリック検定の場合

```ruby
xij = [
     [13.6, 15.6, 9.2],
     [22.3, 23.3, 13.3],
     [26.7, 28.8, 15.0],
     [28.0, 31.2, 15.8],
]
hypothTest2 = Num4HypothTestLib::TwoSideTestLib.new
nonParaTest = Num4DiffTestLib::NonParametrixTestLib.new(hypothTest2)
nonParaTest.mult2_diff_test(xij, a)
=> true
```

