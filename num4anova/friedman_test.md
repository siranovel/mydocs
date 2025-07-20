friedman_test
-------------
フリードマン検定

## 使い方

```ruby
xij = [
    [13.6, 15.6, 9.2],
    [22.3, 23.3, 13.3],
    [26.7, 28.8, 15.0],
    [28.0, 31.2, 15.8],
]
twoWay = Num4AnovaLib::TwoWayLayoutLib.new 
twoWay.friedman_test(xij, 0.05)
=>
  true
```

