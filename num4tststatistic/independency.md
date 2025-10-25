independency
============
独立性の検定量を計算

## 統計的検定
### 検定の手順2

2つの属性AとBの独立性の検定統計量を計算する  
ただし、自由度(m-1)(n-1)の階２乗分布に従う  

## 使い方

```ruby
fij = [
  [57, 33, 46, 14],
  [89, 24, 75, 12],
]
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.independency(fij)
```

