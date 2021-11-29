crtfdist
========
F分布表の作成する

* 使い方  
  $ crtfdist CommonsMath3ModulePath numeratorDegreesOfFreedom degreesOfFreedom | mongoDBurl  
  有意水準:0.05、0.025  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:finv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |nf      |double |
  |df      |double |
  |p       |double |
  |f       |double |
  
* クラス図  
![crtfdist](images/pkgCrtFDist.jpg)

* シーケンス図  
![crtfdist](images/sdCrtFDist.jpg)
