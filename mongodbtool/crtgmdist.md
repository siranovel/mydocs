crtgmdist
=========
Γ分布表の作成する

* 使い方  
  $ crtgmdist CommonsMath3ModulePath shape scale | mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:gminv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |shape   |double |
  |scale   |double |
  |p       |double |
  |ga      |double |
  
* クラス図  
![crtgmdist](images/pkgCrtGMDist.jpg)

* シーケンス図  
![crtgmdist](images/sdCrtGMDist.jpg)
