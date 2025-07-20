crtgndist
=========
スミルノフ・グラブス分布表の作成する

## 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtgndist(df)
```
有意水準:0.050、0.025

## テーブルの型

  DataBase名:distdb  
  コレクション名:gninv  

  |カラム名|型    |
  |-------|------|
  |_id    |ID    |
  |df     |double|
  |p      |double|
  |gn     |double|

