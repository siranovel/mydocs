replicate_plot
--------------
反復測定図

* 使い方

```ruby
vals = {
     "stageA1" => [27, 52, 18, 21, 32],
     "stageA2" => [52, 72, 31, 50, 45],
     "stageA3" => [47, 54, 29, 43, 32],
     "stageA4" => [28, 50, 22, 26, 29],
    }
oneWay = Num4AnovaLib::OneWayLayoutLib.new 
oneWay.replicate_plot("LDH", vals)
```

