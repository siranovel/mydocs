replicate_test
--------------
反復測定検定

* 使い方

```ruby
xi = [
    [27, 52, 18, 21, 32],
    [52, 72, 31, 50, 45],
    [47, 54, 29, 43, 32],
    [28, 50, 22, 26, 29],
]
oneWay = Num4AnovaLib::OneWayLayoutLib.new 
oneWay.replicate_test(xi, 0.05)
=> true
```

