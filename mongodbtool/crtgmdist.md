crtgmdist
=========
ガンマ分布表の作成する

## 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtgmdist(shape, scale)
```
有意水準:0.050

## テーブルの型

  DataBase名:distdb  
  コレクション名:gminv  

  |カラム名|型    |
  |-------|------|
  |_id    |ID    |
  |shape  |double|
  |scale  |double|
  |p      |double|
  |ga     |double|


