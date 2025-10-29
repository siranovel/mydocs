DunnetTestLib
-------------
Dunnet検定

## 統計的検定
### 検定の手順1

対照群と実験群の各組に対して以下の仮説を行う

(1) 両側検定  
・帰無仮設：対照群＝実験群  
・対立仮説：対照群≠実験群  
(2) 片側検定  
・帰無仮設：対照群＝実験群  
・対立仮説：対照群＜実験群  
(3) 片側検定  
・帰無仮設：対照群＝実験群  
・対立仮説：対照群＞実験群  

### 検定の手順2、検定の手順3

検定統計量を計算し、棄却域に入っているかどうか調べる  
棄却域に入っている場合、帰無仮設は棄てる

## 使い方
### 両側検定の場合

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

### 左側検定の場合

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

### 右側検定の場合

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


