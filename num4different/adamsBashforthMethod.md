adamsBashforthMethod
====================
アダムス・バッシュフォース法(k段)による数値計算

## 使い方

```math
\begin{eqnarray}
  a&=&1\\
  \frac{d}{dx}y&=&1.0 + a * x \\
  y(0)&=&1
\end{eqnarray}
```
上記の常微分方程式をアダムス・バッシュフォース法(k段)による解法

```ruby
yi = 1.0
h = 0.001
a = 1
func = Proc.new{|x|
    1.0 + a * x 
}
yi_1 =  Num4DiffLib::adamsBashforthMethod(2, 0, 1, yi, h, func)  
```

