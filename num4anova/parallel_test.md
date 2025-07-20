parallel_test
-------------
回帰直線の平行性検定

## 使い方

```ruby
yi = [
    [3, 5, 3],
    [3, 3, 8],
    [2, 2, 2],
    [3, 4, 2],
    [1, 2, 0],
]
xi = [
   [35, 38, 39],
   [36, 39, 54],
   [40, 45, 39],
   [47, 52, 48],
   [64, 80, 70],
]
ancova = Num4AnovaLib::Num4AncovaLib.new
ancova.parallel_test(yi, xi, 0.05)
=> false
```

