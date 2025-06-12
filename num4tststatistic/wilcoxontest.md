wilcoxontest
============
ウィルコクス符号付き順位検定

* 使い方

```ruby
x = [37.1, 36.2, 36.6, 37.4, 36.8, 36.7, 36.9, 37.4, 36.6, 36.7]
y = [36.8, 36.6, 36.5, 37.0, 36.0, 36.5, 36.6, 37.1, 36.4, 36.7]
nonParaTest = Num4TstStatisticLib::NonParametrixTestLib.new
nonParaTest.wilcoxon(x, y)
```

