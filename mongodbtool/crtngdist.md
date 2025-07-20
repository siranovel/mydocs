crtngdist
=========
仲上分布表の作成する

## 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtnkdist(mu, omega)
```
有意水準:0.050

## テーブルの型

  DataBasee名:distdb  
  コレクション名:nginv  

  |カラム名|型|
  |--------|---|
  |_id     |ID  |
  |mu      |double|
  |omega   |double|
  |p       |double|
  |ng      |double|

