finiteDiffMethod
================
有限差分法による数値計算

## 使い方

```math
\begin{eqnarray}
  \frac{\partial}{\partial{t}}f(x,y,z) &=& 2*x+3*y+4*z+5 \\
  x(0)=y(0)=z(0) &=& 0.0
\end{eqnarray}
```
上記の偏微分方程式を有限差分法による解法

```ruby
yi = [0.0, 0.0, 0.0]
x0 = [0.0, 0.0, 0.0]
h = 0.001
func = Proc.new do | n, xi |
  f = 2 * xi[0] + 3 * xi[1] + 4 * xi[2] + 5
  next f
end
yi_1 = Num4PartialDiffLib.finiteDiffMethod(yi, x0, h, func)
```

