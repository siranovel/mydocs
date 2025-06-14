PoissonRegAna
=============
ポアソン回帰分析

* 使い方

ポアソン回帰分析の場合

```ruby
glsyi = [4, 10, 7, 14]
glsxij = [
    [1],
    [2],
    [3],
    [4],
]
regana = Num4RegAnaLib::PoissonRegAnaLib.new
regana.non_line_reg_ana(glsyi, glsxij)
```

AIC(赤池の情報基準)の場合

```ruby
reg = {
     :intercept => 1.3138,    # 定数項
     :slope    =>  [0.3173],  # 回帰係数
}
xij = [
    [1],
    [2],
    [3],
    [4],
]
regana = Num4RegAnaLib::PoissonRegAnaLib.new
regana.get_aic(reg, xij)
```


