crtexpdist
==========
指数分布表の作成する

* 使い方  
  $ crtexpdist CommonsMath3ModulePath mean| mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:expinv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |mu      |double |
  |p       |double |
  |exp     |double |
  
* クラス図  
![crtexpdist](images/pkgCrtExpDist.jpg)

* シーケンス図  
![crtexpdist](images/sdCrtExpDist.jpg)
