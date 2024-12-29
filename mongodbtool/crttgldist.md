crttgldist
==========
トライアングル分布表の作成する

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crttgldist(a, b, c)
```
有意水準0.050

* テーブルの型
  DataBase名:distdb  
  コレクション名:tglinv  

  |カラム名|型     |
  |--------|------|
  |_id     |ID    |
  |a       |double|
  |b       |double|
  |c       |double|
  |p       |double|
  |tgl     |double|

