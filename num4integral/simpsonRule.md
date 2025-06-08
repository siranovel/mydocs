simpsonRule
===========
ニュートン・コーツ法(2次:シンプソンの公式)

* 使い方

```ruby
h = 0.001
func = Proc.new{|x|
    next 4 / (1 + x * x)
}
y = Num4InteLib.simpsonRule(0, 1, h, func)
```

