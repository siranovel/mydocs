crtcauchydist
=============
コーシー分布表の作成する

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtcauchydist(median, scale)
```
有意水準:0.050

* テーブルの型

  DataBase名:distdb  
  コレクション名:cauchyinv  

  |カラム名|型     |
  |--------|------|
  |_id     |ID    |
  |median  |double|
  |scale   |double|
  |p       |double|
  |cachy   |double|
  
