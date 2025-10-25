fidelity
========
適合度の検定量を計算

## 統計的検定
### 検定の手順2

N個の適合度の検定量を計算する  
ただし、自由度N−１の階２乗分布に従う
(num4hypothtstを使用して棄却域に入っているかどうか判定する)


## 使い方

```ruby
fi = [57, 33, 46, 14]
pi = [0.4, 0.2, 0.3, 0.1]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.fidelity(fi, pi)
```

