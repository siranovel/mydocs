crtfdist
========
F分布表の作成する

## 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBCrtLib.new
mongo.crtfdist(nf, df)
```
有意水準:0.05、0.025

## テーブルの型

  DataBase名:distdb  
  コレクション名:finv  

  |カラム名|型     |
  |--------|------|
  |_id     |ID    |
  |nf      |double|
  |df      |double|
  |p       |double|
  |f       |double|

