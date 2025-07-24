rungeKuttaMethod
================
4次のルンゲ＝クッタ法による数値計算

## 使い方

```math
\left\{
  \begin{aligned}
    u&=&\frac{d}{dt}y \\
    \frac{d}{dt}u&=&y
  \end{aligned}
\right.
y(0)=u(0)=1.0
```
上記の一次連立常微分方程式を4次のルンゲ＝クッタ法による解法

```ruby
func = Proc.new do | n, yi |
  f = []
  f[0] = yi[0]
  f[1] = yi[1]
  next f
end
yi = [1.0, 1.0] 
yi_1 =  Num4SimDiffLib.rungeKuttaMethod(yi, 0.001, func)
```

