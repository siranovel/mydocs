crtbidist
===========
2項分布表の作成する

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtbidist(trials, mu)
```
有意水準:0.050

* テーブルの型
  DataBase名: distdb  
  コレクション名: bebi  

  |カラム名|型     |
  |--------|------|
  |_id     |ID    |
  |n       |int32 |
  |a       |double|
  |b       |double|
  |x       |double|
  |p       |double|
