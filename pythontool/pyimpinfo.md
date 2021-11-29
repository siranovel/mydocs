pyimpinfo
=========
pythonのimp情報表示

* 表示項目
  - 定数
  - suffixs
  - suffix
  - mode
  - type

* 使い方  
$ pyimpinfo

* 出力サンプル  

<pre>
$ pyimpinfo
-----------------------------
定数
-----------------------------
SEARCH_ERROR:0
PY_SOURCE:1
PY_COMPILED:2
C_EXTENSION:3
PY_RESOURCE:4
PKG_DIRECTORY:5
C_BUILTIN:6
PY_FROZEN:7
PY_CODERESOURCE:8
IMP_HOOK:9
-----------------------------
Suffixes
-----------------------------
suffix: .so
mode  : rb
type  : extension

suffix: module.so
mode  : rb
type  : extension

suffix: .py
mode  : U
type  : source

suffix: .pyc
mode  : rb
type  : compiled

</pre>

* クラス図  
![pyimpinfo](images/pkgPyImpInfo.jpg)

* シーケンス図  
![pyimpinfo](images/sdPyImpInfo.jpg)
