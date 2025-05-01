oneway_scatter_plot
-------------------
一元散布図

* 使い方

```ruby
vals = {
      "stage51" => [12.2, 18.8, 18.2],
      "stage55" => [22.2, 20.5, 14.6],
      "stage57" => [20.8, 19.5, 26.3],
      "stage59" => [26.4, 32.5, 31.3],
      "stage61" => [24.5, 21.2, 22.4],
    }
oneWay = Num4AnovaLib::OneWayLayoutLib.new 
oneWay.oneway_scatter_plot("LDH", vals)
```

