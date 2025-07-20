crtzipfdist
===========
Zipf分布表の作成する

## 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtzipfdist(n, exponent)
```

## テーブルの型

  DataBase名:distdb  
  コレクション名:zipfinv  

  |カラム名 |型    |
  |_id     |ID    |
  |elm     |int32 |
  |exponent|double|
  |p       |double|
  |zipf    |double|

