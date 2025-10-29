bonferrono_test
---------------
ボンフェロー二の不等式による多重比較  

## 統計的検定
### 検定の手順1

全ての組み合わせに対して、以下の仮説を立てる  
・帰無仮設：平均の差が無い  
・対立仮説：平均の差が有る

### 検定の手順2,検定の手順3

全ての組み合わせに対して、以下のことをする  
検定統計量を計算し、棄却域に入っているかどうか調べる  
棄却域に入っている場合、帰無仮設は棄てる

## 使い方
### パラメトリック検定の場合  

  T検定による多重検定

```ruby
xi = [
    [12.2, 18.8, 18.2],
    [22.2, 20.5, 14.6],
    [20.8, 19.5, 26.3],
    [26.4, 32.5, 31.3],
    [24.5, 21.2, 22.4],
]
paraTest = MultiCompLib::ParametrixTestLib.new
paraTest.bonferrono_test(xi, 0.05)
=> 
  [
    [false, false, false, true, false],
    [false, false, false, true, false],
    [false, false, false, false, false],
    [false, false, false, false, false],
    [false, false, false, false, false],
  ]
```

### ノンパラメトリック検定の場合  

  U検定による多重検定

```ruby
xi = [
    [12.2, 18.8, 18.2],
    [22.2, 20.5, 14.6],
    [20.8, 19.5, 26.3],
    [26.4, 32.5, 31.3],
    [24.5, 21.2, 22.4],
]
nonParaTest = MultiCompLib::NonParametrixTestLib.new
nonParaTest.bonferrono_test(xi, 0.05)
=> 
  [
    [false, false, true,  true,  true],
    [false, false, false, true,  true],
    [false, false, false, true,  false],
    [false, false, false, false, true],
    [false, false, false, false, false],
 ]
```

