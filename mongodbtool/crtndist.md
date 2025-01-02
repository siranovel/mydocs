crtndist
========
正規分布表の作成する

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtndist
```

* テーブルの型

  DataBase名:distdb  
  コレクション名:norminv  

  |カラム名|型     |
  |--------|------|
  |_id     |ID    |
  |p       |double|
  |z       |double|

