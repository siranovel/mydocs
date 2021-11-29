crthgedist
=========
超幾何分布表の作成する

* 使い方  
  $ crthgedist CommonsMath3ModulePath populationSize | mongoDBurl  
  有意水準:0.050  

* テーブルの型  
  DataBase名:distdb  
  コレクション名:hgeinv  

  |カラム名|型     |
  |--------|-------|
  |_id     |ID     |
  |popsz   |int32  |
  |num     |int32  |
  |smplsz  |int32  |
  |p       |double |
  |ga      |int32  |
  
* クラス図  
![crthgedist](images/pkgCrtHGeDist.jpg)

* シーケンス図  
![crthgedist](images/sdCrtHGeDist.jpg)
