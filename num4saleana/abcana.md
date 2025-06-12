abcana
======
ABC分析

* 使い方

```ruby
sales_info = [
     {"name" => "商品1", "revenue" => 2400000},
     {"name" => "商品2", "revenue" => 1200000},
     {"name" => "商品3", "revenue" => 1000000},
     {"name" => "商品4", "revenue" => 600000},
     {"name" => "商品5", "revenue" => 270000},
]
sale = Num4SaleAnaLib::SalesAnaLib.new
sale.abcana(sales_info)
```

