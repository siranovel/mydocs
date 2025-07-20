smple_line_reg_ana
==================
単回帰による効果推定

## 使い方

```ruby
yi = [300, 600, 500, 400, 300, 500, 600, 400, 500, 300]
zi = [  0,   1,   0,   1,   0,   0,   1,   1,   0,   0]  
regana = Num4RegAnaLib::RCTLib.new
regana.smple_line_reg_ana(yi, zi)
```

