crtlogndist
===========
対数正規分布表の作成する

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtlogndist
```

* テーブルの型
  DataBase名:distdb  
  コレクション名:lognorminv  

  |カラム名|型     |
  |--------|------|
  |id      |ID    |
  |p       |double|
  |logz    |double|

