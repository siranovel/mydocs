crtngdist
=========
仲上分布表の作成する

* 使い方  
  $ crtngdist CommonsMath3ModulePath mu omega | mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:nginv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |mu      |double |
  |omega   |double |
  |p       |double |
  |ng      |double |
  
* クラス図  
![crtngdist](images/pkgCrtNGDist.jpg)

* シーケンス図  
![crtngdist](images/sdCrtNGDist.jpg)
