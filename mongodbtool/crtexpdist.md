crtexpdist
==========
指数分布表の作成する

## 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtexpdist(mean)
```
有意水準:0.050

## テーブルの型

  DataBase名:distdb  
  コレクション名:expinv  

  |カラム名|型|
  |--------|---|
  |_id     |ID|
  |mu      |double|
  |p       |double|
  |exp     |double|

