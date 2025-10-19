independency
============
２つの属性AとBが独立かどうかの検定

## 統計的検定
### 検定の手順1

　・帰無仮設：２つの奥性AとBは独立である
　・対立仮説：２つの属性Aとの間には関連がある

### 検定の手順2、検定の手順3

検定統計量を計算し、棄却域に入っているかどうか調べる  
棄却域に入っている場合、帰無仮設は棄てる

## 使い方

```ruby
fij = [
  [57, 33, 46, 14],
  [89, 24, 75, 12],
]
hypothTest = Num4HypothTestLib::RightSideTestLib.new
paraTest = Num4TstStatistic2Lib::ParametrixTestLib.new(hypothTest)
paraTest.independency(fij, 0.05)
```

