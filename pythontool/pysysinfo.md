pysysinfo
=========
pythonのsys情報表示

* 表示項目
  - platform、path、version、copyright
  - prefix  
    prefix、exec_prefix  
  - Encoding
  fileSystemEncoding、defaultEncoding  


* 使い方  
$ pysysinfo

* 出力サンプル  

<pre>
$ pysysinfo
platform:linux2
prefix     :/usr
exec_prefix:/usr
fileSystemEncoding:UTF-8
defaultEncoding:ascii

        /usr/lib64/python26.zip
        /usr/lib64/python2.6
        /usr/lib64/python2.6/plat-linux2
        /usr/lib64/python2.6/lib-tk
        /usr/lib64/python2.6/lib-old
        /usr/lib64/python2.6/lib-dynload
        /usr/lib64/python2.6/site-packages
        /usr/lib64/python2.6/site-packages/Numeric
        /usr/lib64/python2.6/site-packages/PIL
        /usr/lib64/python2.6/site-packages/gst-0.10
        /usr/lib64/python2.6/site-packages/gtk-2.0
        /usr/lib/python2.6/site-packages
-----------------------------------
        version
-----------------------------------
2.6.6 (r266:84292, Mar  4 2014, 20:48:09)
[GCC 4.4.5 20101001 (Vine Linux 4.4.5-6.1vl6)]
-----------------------------------
        copyright
-----------------------------------
Copyright (c) 2001-2010 Python Software Foundation.
All Rights Reserved.

Copyright (c) 2000 BeOpen.com.
All Rights Reserved.

Copyright (c) 1995-2001 Corporation for National Research Initiatives.
All Rights Reserved.

Copyright (c) 1991-1995 Stichting Mathematisch Centrum, Amsterdam.
All Rights Reserved.
</pre>

* クラス図  
![pysysinfo](images/pkgPySysInfo.jpg)

* シーケンス図  
![pysysinfo](images/sdPySysInfo.jpg)

