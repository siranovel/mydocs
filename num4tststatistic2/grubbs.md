grubbs
======
グラプス・スミルノフの外れ値の検定

* 使い方

```ruby
xi = [3.4, 3.5, 3.3, 2.2, 3.3, 3.4, 3.6, 3.2]
outlier = Num4TstStatistic2Lib::OutlierLib.new
outlier.grubbs(xi, 2.2, 0.05)
```

