rbconfig
========
rubyのRbConfig::CONFIG情報を表示

* 表示項目
  - topdir
  - build_os
  - host_os
  - host_cpu
  - includedir, libdir, rubylibdir
  - archdir, htmldir, pdfdir
  - sitearchdir, vendorarchdir  

* 使い方  
$ rbconfig

* 出力サンプル  

<pre>
$ rbconfig
       topdir:/usr
     build_os:linux-gnu
      host_os:linux-gnu
     host_cpu:x86_64
   includedir:/usr/include
       libdir:/usr/lib64
   rubylibdir:/usr/lib/ruby/1.8
      archdir:/usr/lib64/ruby/1.8/x86_64-linux
      htmldir:/usr/share/doc/$(PACKAGE)
       pdfdir:/usr/share/doc/$(PACKAGE)
  sitearchdir:/usr/local/lib64/site_ruby/1.8/x86_64-linux
vendorarchdir:/usr/lib64/ruby/vendor_ruby/1.8/x86_64-linux
</pre>

* クラス図  
![rbconfig](images/pkgRbConfig.jpg)

* シーケンス図
![rbconfig](images/sdRbConfig.jpg)
