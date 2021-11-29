pysysconfiginfo
===============
pythonのsysconfig情報表示


* 表示項目
  - PREFIX
  - EXEC_PREFIX
  - python_version
  - python_inc
  - python_lib  

* 使い方  
$ pysysconfiginfo

* 出力サンプル  

<pre>
$ pysysconfiginfo
python_build:False
PREFIX:/usr
EXEC_PREFIX:/usr
python_version:2.6
python_inc:/usr/include/python2.6
python_lib:/usr/lib/python2.6/site-packages
</pre>

* クラス図  
![pysysconfiginfo](images/pkgPyySysConfiginfo.jpg)

* シーケンス図
![pysysconfiginfo](images/sdPySysConfigInfo.jpg)
