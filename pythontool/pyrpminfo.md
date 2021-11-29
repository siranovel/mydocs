pyrpminfo
=========
rpmファイル情報を表示

* 表示項目
  - rpmのversion
  - Name-Version-Release
  - Distribution
  - Vendor
  - License
  - Packager  

* 使い方  
$ pyrpminfo rpmファイル

* 出力サンプル  

<pre>
$ pyrpminfo pythontool-pyrpminfo-1.0-3.noarch.rpm
rpm version:4.8.1
pythontool-pyrpminfo-1.0-3
Distribution:Vine Linux
Vendor:Project Vine
License:MIT
Packager:paradox <siranovel@gmail.com>
</pre>

* クラス図  
![pyrpminfo](images/pkgPyRpmInfo.jpg)

* シーケンス図  
![pyrpminfo](images/sdPyRpmInfo.jpg)
