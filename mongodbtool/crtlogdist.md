crtlogdist
=========
ロジスティック分布表の作成する

* 使い方  
  $ crtlogdist CommonsMath3ModulePath mu s | mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:loginv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |mu      |double |
  |s       |double |
  |p       |double |
  |lg      |double |
  
* クラス図  
![crtlogdist](images/pkgCrtLogDist.jpg)

* シーケンス図  
![crtlogdist](images/sdCrtLogDist.jpg)
