finiteDiffMethod
================
有限差分法による数値計算

## 使い方

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

