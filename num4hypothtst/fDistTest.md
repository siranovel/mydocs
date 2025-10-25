fDistTest
---------
検定統計量は、F分布の棄却域に入っているかどうかcheckする

## 統計的検定
### 検定の手順3

"検定統計量が棄却域に入るとき、帰無仮設を棄てる"  
これは、次のことと同じです  
"有意確率 ≦ 有意水準の時、帰無仮設を棄てる"  
　検定統計量の有意確率(検定統計量の外側の確率)

## 使い方
### 両側検定の場合

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::TwoSideTestLib.new
hypothTest.fDistTest(0.4727, 11, 7, a)
```

### 片側(右側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::RightSideTestLib.new
hypothTest.fDistTest(0.4727, 11, 7, a)
```

### 片側(左側)検定

```ruby
a = 0.05
hypothTest = Num4HypothTestLib::LeftSideTestLib.new
                      hypothTest.fDistTest(0.4727, 11, 7, a)
```

