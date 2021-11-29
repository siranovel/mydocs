crtcauchydist
=============
コーシー分布表の作成する

* 使い方  
  $ crtcauchydist CommonsMath3ModulePath mean scale | mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:cauchyinv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |median  |double |
  |scale   |double |
  |p       |double |
  |cachy   |double |
  
* クラス図  
![crtcauchydist](images/pkgCrtCauchyDist.jpg)

* シーケンス図  
![crtcauchydist](images/sdCrtCauchyDist.jpg)
