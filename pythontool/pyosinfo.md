pyosinfo
========
pythonのos情報表示

* 表示項目
  - uname
  - id情報
    uid、gid、groups、egid、euid  
  - devnull
  - login
  - ppid
  - pid
  - pardir
  - sep
  - defpath
  - cwd
  - name  

* 使い方  
$ pyosinfo

* 出力サンプル  

<pre>
$ pyosinfo
uname:
        Linux localhost.localdomain 4.4.52-2vl6 #1 SMP Tue Mar 7 13:38:49 JST 20
17 x86_64
uid:500 gid:500 groups:500
egid:500 euid:500
devnull:/dev/null
login:sira
ppid:2956 pid:3106
pardir:.. curdir:.
sep:/
defpath::/bin:/usr/bin
cwd:/home/sira/git/pythontool.wiki
name:posix
</pre>

* クラス図  
![pyosinfo](images/pkgPyOsInfo.jpg)

* シーケンス図  
![pyosinfo](images/sdPyOsInfo.jpg)
