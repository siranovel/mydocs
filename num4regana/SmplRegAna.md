SmplRegAna
----------
単回帰分析

* 使い方

単回帰分析の場合

```ruby
yi = [286, 851, 589, 389, 158, 1037, 463, 563, 372, 1020]
xi = [107, 336, 233,  82,  61,  378, 129, 313, 142,  428]
regana = Num4RegAnaLib::SmplRegAnaLib.new
regana.line_reg_ana(yi, xi)
=> 
  {
     "intercept":  99.075, # 定数項
     "slope":      2.145,  # 回帰係数
  }
```

決定係数の場合

```ruby
yi = [286, 851, 589, 389, 158, 1037, 463, 563, 372, 1020]
xi = [107, 336, 233,  82,  61,  378, 129, 313, 142,  428]
regana = Num4RegAnaLib::SmplRegAnaLib.new
regana.getr2(yi, xi)
=> 0.893
```

相関係数の場合

```ruby
yi = [286, 851, 589, 389, 158, 1037, 463, 563, 372, 1020]
xi = [107, 336, 233,  82,  61,  378, 129, 313, 142,  428]
regana = Num4RegAnaLib::SmplRegAnaLib.new
regana.getr(yi, xi)
=> 0.945
```



