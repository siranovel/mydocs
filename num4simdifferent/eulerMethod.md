eulerMethod
===========
オイラー法による数値計算

## 使い方

```math
\begin{eqnarray}
  \left\{
    \begin{array}
      u=\frac{d}{dt}y\\
      \frac{d}{dt}u=y
    \end{array}
  \right.
\end{eqnarray}
  y(0)=1.0 u(0)=1.0
```
上記の一次連立常微分方程式をオイラー法による解法

```ruby
func = Proc.new do | n, yi |
  f = []
  f[0] = yi[0]
  f[1] = yi[1]
  next f
end
yi = [1.0, 1.0] 
yi_1 =  Num4SimDiffLib.eulerMethod(yi, 0.001, func)
```


