crtgudist
=========
ガンベル分布表の作成する

* 使い方  
  $ crtgudist CommonsMath3ModulePath mu beta | mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:guinv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |mu      |double |
  |beta    |double |
  |p       |double |
  |gu      |double |
  
* クラス図  
![crtgudist](images/pkgCrtGUDist.jpg)

* シーケンス図  
![crtgudist](images/sdCrtGUDist.jpg)
