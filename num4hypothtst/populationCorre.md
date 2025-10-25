populationCorre
---------------
標準相関係数から、検定統計量を計算し、標準正規分布の棄却域に入っているかどうかcheckする  

## 統計的検定
### 検定の手順2

標準相関係数から、検定統計量を計算

### 検定の手順3

標準相関係数から、検定統計量を計算  
"検定統計量が棄却域に入るとき、帰無仮設を棄てる"  
これは、次のことと同じです  
"有意確率 ≦ 有意水準の時、帰無仮設を棄てる"  
　検定統計量の有意確率(検定統計量の外側の確率)

## 使い方
### 両側検定の場合

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
hypothTest.populationCorre(-0.76655, 12, -0.3, a)
```

### 片側(右側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::RightSideTestLib.new
hypothTest.populationCorre(-0.76655, 12, -0.3, a)
```

### 片側(左側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::LeftSideTestLib.new
hypothTest.populationCorre(-0.76655, 12, -0.3, a)
```

