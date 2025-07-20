PoissonHierBayesRegAna
======================
ポアソン回帰分析

## 使い方
### ポアソン回帰分析の場合

```ruby
glsyi = [4, 10, 7, 14]
glsxij = [
    [1],
    [2],
    [3],
    [4],
]
regana = Num4RegAnaLib::HierBayesPoissonRegAnaLib.new
regana.non_line_reg_ana(glsyi, glsxij)
```

