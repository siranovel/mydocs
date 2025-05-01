DunnetTestLib
-------------
Dunnet検定

* 使い方

両側検定の場合

```ruby
xi = [
    [12.2, 18.8, 18.2],
    [22.2, 20.5, 14.6],
    [20.8, 19.5, 26.3],
    [26.4, 32.5, 31.3],
    [24.5, 21.2, 22.4],
]
paraTest = MultiCompLib::ParametrixTestLib.new
paraTest.twoside_test(xi, 0.05)
=> 
  res = [
      [false, false, false, true, false],
      [false, false, false, true, false],
      [false, false, false, false, false],
      [true,  true,  false, false, false],
      [false, false, false, false, false],
  ]
```

左側検定の場合

```ruby
xi = [
    [12.2, 18.8, 18.2],
    [22.2, 20.5, 14.6],
    [20.8, 19.5, 26.3],
    [26.4, 32.5, 31.3],
    [24.5, 21.2, 22.4],
]
paraTest = MultiCompLib::ParametrixTestLib.new
paraTest.leftside_test(xi, 0.05)
=> 
  res = [
      [false, false, false, false, false],
      [false, false, false, false, false],
      [true,  false, false, false, false],
      [true,  true,  true,  false, true],
      [true,  false, false, false, false],
  ]
```

右側検定の場合

```ruby
xi = [
    [12.2, 18.8, 18.2],
    [22.2, 20.5, 14.6],
    [20.8, 19.5, 26.3],
    [26.4, 32.5, 31.3],
    [24.5, 21.2, 22.4],
]
paraTest = MultiCompLib::ParametrixTestLib.new
paraTest.rightside_test(xi, 0.05)
=> 
  res = [
      [false, false, true,  true,  true],
      [false, false, false, true,  false],
      [false, false, false, true,  false],
      [false, false, false, false, false],
      [false, false, false, true, false],
  ]
```


