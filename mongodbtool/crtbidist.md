crtbidist
=========
２項分布表の作成する

* 使い方  
  $ crtbidist CommonsMath3ModulePath trials mu | mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:biinv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |n       |int32  |
  |mu      |double |
  |p       |double |
  |bi      |int32  |
  
* クラス図  
![crtbidist](images/pkgCrtBiDist.jpg)

* シーケンス図  
![crtbidist](images/sdCrtBiDist.jpg)
