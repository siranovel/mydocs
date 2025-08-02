eulerMethod
===========
オイラー法による数値計算

## 使い方

$$
\begin{eqnarray}
  a&=&1\\
  \frac{d}{dx}y&=&1.0 + a * x \\
  y(0)&=&1
\end{eqnarray}
$$
上記の常微分方程式をオイラー方による解法

```ruby
yi = 1.0
h = 0.001
a = 1
func = Proc.new{|x|
    1.0 + a * x 
}
yi_1 =  Num4DiffLib::eulerMethod(yi, 0.0, h, func)  
```

