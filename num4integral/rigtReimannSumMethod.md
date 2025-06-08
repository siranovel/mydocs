rigtReimannSumMethod
====================
右リーマン和による数値計算

* 使い方

```ruby
h = 0.001
func = Proc.new{|x|
    next 4 / (1 + x * x)
}
y = Num4InteLib.rigtReimannSumMethod(0, 1, h, func)
```

