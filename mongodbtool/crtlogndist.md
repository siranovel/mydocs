crtlogndist
========
対数正規分布表の作成する

* 使い方  
  $ crtlogndist CommonsMath3ModulePath | mongoDBurl

* テーブルの型  
  DataBase名:distdb  
  コレクション名:lognorminv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |p       |double |
  |logz    |double |
  
* クラス図  
![crtlogndist](images/pkgCrtLogNDist.jpg)

* シーケンス図  
![crtlogndist](images/sdCrtLogNDist.jpg)
