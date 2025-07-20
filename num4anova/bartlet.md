bartlet
-------
バートレット検定

## 使い方

```ruby
xi = [
    [12.2, 18.8, 18.2],
    [22.2, 20.5, 14.6],
    [20.8, 19.5, 26.3],
    [26.4, 32.5, 31.3],
    [24.5, 21.2, 22.4],
]
oneWay = Num4AnovaLib::OneWayLayoutLib.new 
oneWay.bartlet(xi, 0.05)
=> true
```

