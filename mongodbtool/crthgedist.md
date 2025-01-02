crthgedist
==========
超幾何分布表の作成する

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crthgedist(populationSize)
```
有意水準:0.050

* テーブルの型

  Database名:distdb  
  コレクション名:hgeinv  

  |カラム名|型    |
  |-------|------|
  |_id    |ID    |
  |popsz  |int32 |
  |num    |int32 |
  |smplsz |int32 |
  |p      |double|
  |ga     |double|
