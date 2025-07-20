newtonMethod
============
ニュートン法による数値計算

## 使い方

```math
f(x)=x^2-2=0
```
上記の方程式を、ニュートン法による解法

```ruby
f1 = proc {|x| 
    next x * x - 2
}
x = Num4EquLib.newtonMethod(-1.8, f1)
```

