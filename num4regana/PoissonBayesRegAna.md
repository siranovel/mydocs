PoissonBayesRegAna
==================
ベイズポアソン回帰分析

* 使い方

ベイズポアソン回帰分析の場合

```ruby
glsyi = [4, 10, 7, 14]
glsxij = [
    [1],
    [2],
    [3],
    [4],
]
regana = Num4GLMMRegAnaLib::PoissonBayesRegAnaLib.new
regana.non_line_reg_ana(glsyi, glsxij)
```

BIC(ベイズ情報基準)の場合

```ruby
reg = {
     :intercept=>0.4341885635221602, # 定数項
     :slope=>[0.5703137378188881]    # 回帰係数
}
xij = [
    [1],
    [2],
    [3],
    [4],
]
regana = Num4GLMMRegAnaLib::BayesPoissonRegAnaLib.new
regana.get_bic(reg, xij)
```



