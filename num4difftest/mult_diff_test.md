mult_diff_test
--------------
3群以上の母平均の差の検定(1元配置)

## 概要
### パラメトリックの場合

反復データがある場合：反復測定による一元配置の分散分析  
反復データがない場合：一元配置分散分析  

### ノンパラメトリックの場合

クラスカル・ウォリスの検定(対応の無い場合)をする

## 使い方
### パラメトリック検定の場合

```ruby
xi = [
     [12.2, 18.8, 18.2],
     [22.2, 20.5, 14.6],
     [20.8, 19.5, 26.3],
     [26.4, 32.5, 31.3],
     [24.5, 21.2, 22.4],
]
hypothTest2 = Num4HypothTestLib::TwoSideTestLib.new
paraTest2 = Num4DiffTestLib::ParametrixTestLib.new(hypothTest2)
paraTest2.mult_diff_test(xi, 0.05)
=> false
```

### ノンパラメトリック検定の場合

```ruby
xi = [
     [12.2, 18.8, 18.2],
     [22.2, 20.5, 14.6, 20.8, 19.5, 26.3],
     [26.4, 32.5, 31.3, 24.5, 21.2, 22.4],
]
hypothTest2 = Num4HypothTestLib::TwoSideTestLib.new
nonParaTest = Num4DiffTestLib::NonParametrixTestLib.new(hypothTest2)
nonParaTest.mult_diff_test(xi, 0.05)
=> false
```

