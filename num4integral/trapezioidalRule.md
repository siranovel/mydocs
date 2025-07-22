trapezioidalRule
================
ニュートン・コーツ法(1次:台形公式)による数値計算

## 使い方

```math
\int_{0}^{1} \frac{4}{1 + x^2} dx
```
上記の定積分をニュートン・コーツ法(1次:台形公式)による解法

```ruby
h = 0.001
func = Proc.new{|x|
    next 4 / (1 + x * x)
}
y = Num4InteLib.trapezioidalRule(0, 1, h, func)
```

