pysiteinfo
==========
pythonのsite情報表示

* 表示項目
  - check_enableusersite
  - ENABLE_USER_SITE
  - USER_SITE
  - USER_BASE
  - PREFIXES
  - site module  


* 使い方  
$ pysiteinfo

* 出力サンプル  

<pre>
$ pysiteinfo
dirname:/usr/lib/python2.6/site-packages
dirname:/home/sira/.local/lib/python2.6/site-packages
check_enableusersite:True
ENABLE_USER_SITE:True
USER_SITE:/home/sira/.local/lib/python2.6/site-packages
USER_BASE:/home/sira/.local
        /usr
        /usr
site module
</pre>

* クラス図  
![pysiteinfo](images/pkgPySiteInfo.jpg)

* シーケンス図  
![pysiteinfo](images/sdPySiteInfo.jpg)
