crtparetodist
=============
パレット分布表の作成する

* 使い方  
  $ crtparetodist CommonsMath3ModulePath | mongoDBurl

* テーブルの型  
  DataBase名:distdb  
  コレクション名:gpinv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |p       |double |
  |pareto  |double |
  
* クラス図  
![crtndist](images/pkgCrtParetoDist.jpg)

* シーケンス図  
![crtndist](images/sdCrtParetoDist.jpg)
