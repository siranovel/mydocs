secantMethod
============
割線法による数値計算

* 使い方

```ruby
f1 = proc {|x| 
  next x * x - 2
}
x = Num4EquLib.secantMethod(-1, 3, f1)
```

