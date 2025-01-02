crtwbldist
==========
ワイブル分布表の作成する

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtwbldist(alpha, beta)
```
有意水準:0.050

* テーブルの型

  DataBase名:distdb  
  コレクション名:wblinv  

  |カラム名|型     |
  |--------|------|
  |_id     |ID    |
  |alpa    |double|
  |beta    |double|
  |p       |double|
  |wbl     |double|

