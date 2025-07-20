crtpodist
=========
ポイソン分布表の作成する

## 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtpodist(lambda)
```
有意水準:0.050

## テーブルの型

  DataBase名:distdb  
  コレクション名:poinv  

  |カラム名|型     |
  |--------|------|
  |_id     |ID    |
  |lamda   |double|
  |p       |double|
  |po      |int32 |

