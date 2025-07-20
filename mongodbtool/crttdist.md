crttdist
========
T分布表の作成する

## 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crttdist(df)
```
有意水準:0.25、0.1、0.05、0.025、0.01、0.005

## テーブルの型

  DataBase名:distdb  
  コレクション名:tinv  

  |カラム名|型    |
  |-------|------|
  |_id    |ID    |
  |df     |double|
  |p      |double|
  |t      |double|

