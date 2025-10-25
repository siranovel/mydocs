GrubbsTest
----------
グラブス・スミルノフの外れ値の検定(正規分布を仮定する)

## 統計的検定
### 検定の手順3

検定統計量
"検定統計量が棄却域に入るとき、帰無仮設を棄てる"  
これは、次のことと同じです  
"有意確率 ≦ 有意水準の時、帰無仮設を棄てる"  
　検定統計量の有意確率(検定統計量の外側の確率)


## 使い方
### 両側検定の場合

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::GrubbsTestLib.new
hypothTest.twoSideTest(2.3724, 8, a)
```

### 片側検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::GrubbsTestLib.new
hypothTest.oneSideTest(2.3724, 8, a)
```

