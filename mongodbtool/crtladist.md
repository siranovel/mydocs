crtladist
=========
ラプラス分布表の作成する

* 使い方  
  $ crtladist CommonsMath3ModulePath mu beta | mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:lainv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |mu      |double |
  |beta    |double |
  |p       |double |
  |la      |double |
  
* クラス図  
![crtladist](images/pkgCrtLaDist.jpg)

* シーケンス図  
![crtladist](images/sdCrtLaDist.jpg)
