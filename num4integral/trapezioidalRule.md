trapezioidalRule
================
ニュートン・コーツ法(1次:台形公式)

* 使い方

```ruby
h = 0.001
func = Proc.new{|x|
    next 4 / (1 + x * x)
}
y = Num4InteLib.trapezioidalRule(0, 1, h, func)
```

