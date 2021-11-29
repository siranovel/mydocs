pyrpmtaginfo
============
rpmのtagnames情報表示


* 表示項目
  - no
  - TAG名
  - TAG定数  

* 使い方  
$ pyrpmtaginfo

* 出力サンプル  

<pre>
$ pyrpmtaginfo
  61 HEADERIMAGE          RPMTAG_HEADERIMAGE
  62 HEADERSIGNATURES     RPMTAG_HEADERSIGNATURES
  63 HEADERIMMUTABLE      RPMTAG_HEADERIMMUTABLE
  64 HEADERREGIONS        RPMTAG_HEADERREGIONS
 100 HEADERI18NTABLE      RPMTAG_HEADERI18NTABLE
 257 SIGSIZE              RPMTAG_SIGSIZE
 259 SIGPGP               RPMTAG_SIGPGP
 261 SIGMD5               RPMTAG_PKGID RPMTAG_SIGMD5
 262 SIGGPG               RPMTAG_SIGGPG
 266 PUBKEYS              RPMTAG_PUBKEYS
 267 DSAHEADER            RPMTAG_DSAHEADER
 268 RSAHEADER            RPMTAG_RSAHEADER
 269 SHA1HEADER           RPMTAG_HDRID RPMTAG_SHA1HEADER
 270 LONGSIGSIZE          RPMTAG_LONGSIGSIZE
 271 LONGARCHIVESIZE      RPMTAG_LONGARCHIVESIZE
1000 NAME                 RPMTAG_N RPMTAG_NAME
1001 VERSION              RPMTAG_V RPMTAG_VERSION
1002 RELEASE              RPMTAG_R RPMTAG_RELEASE
1003 EPOCH                RPMTAG_E RPMTAG_EPOCH
1004 SUMMARY              RPMTAG_SUMMARY
...
</pre>

* クラス図  
![pyrpmtaginfo](images/pkgPyRpmTagInfo.jpg)

* シーケンス図  
![pyrpmtaginfo](images/sdPyRpmTagInfo.jpg)