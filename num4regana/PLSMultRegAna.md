PLSMultRegAna
=============
部分的最小二乗法(PLS)による回帰分析を行う

## 概要

## 使い方

```ruby
olsyi = [45, 38, 41, 34, 59, 47, 35, 43, 54, 52]
olsxij = [
    [17.5, 30],
    [17.0, 25],
    [18.5, 20],
    [16.0, 30],
    [19.0, 45],
    [19.5, 35],
    [16.0, 25],
    [18.0, 35],
    [19.0, 35],
    [19.5, 40],
]
regana = Num4RegAnaLib::PLSMultRegAnaLib.new
regana.line_reg_ana(olsyi, olsxij)
```

