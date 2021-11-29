crtpodist
=========
ポイソン分布表の作成する

* 使い方  
  $ crtpodist CommonsMath3ModulePath lamda | mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:poinv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |lamda   |double |
  |p       |double |
  |po      |int32  |
  
* クラス図  
![crtpodist](images/pkgCrtPoDist.jpg)

* シーケンス図  
![crtpodist](images/sdCrtPoDist.jpg)
