adamsMoultonMethod
==================
アダムス・ムルトン法(k段)による数値計算

## 使い方

```ruby
yi = 1.0
h = 0.001
a = 1
func = Proc.new{|x|
    1.0 + a * x 
}
yi_1 =  Num4DiffLib::adamsMoultonMethod(2, 0, 1, yi, h, func)  
```

