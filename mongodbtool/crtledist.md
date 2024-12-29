crtledist
=========
レヴェ分布表の作成する

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtledist(mu, c)
```
有意水準:0.050

* テーブルの型
  DataBase名:distdb  
  コレクション名:leinv  

  |カラム名|型     |
  |_id     |ID    |
  |mu      |double|
  |c       |double|
  |p       |double|
  |le      |double|

