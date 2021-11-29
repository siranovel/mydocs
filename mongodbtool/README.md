mongodbtool
===========
commons-math3を利用して、分布表のデータをmongodbに格納ツールです。

* ツールの種類
  - crtdist
    - [crtndist](crtndist)
    - [crtlogndist](crtlogndist)
    - [crttdist](crttdist)
    - [crtfdist](crtfdist)
    - [crtparetodist](crtparetodist)
    - [crtzipfdist](crtzipfdist)
    - [crtbebidist](crtbebidist)
    - [crtchi2dist](crtchi2dist)
    - [crtexpdist](crtexpdist)
    - [crtbidist](crtbidist)
    - [crtgmdist](crtgmdist)
    - [crtgudist](crtgudist)
    - [crthgedist](crthgedist)
    - [crtgndist](crtgndist)
    - [crtladist](crtladist)
    - [crtledist](crtledist)
    - [crtlogdist](crtlogdist)
    - [crtngdist](crtngdist)
    - [crtpodist](crtpodist)
    - [crttgldist](crttgldist)
    - [crtwbldist](crtwbldist)
    - [crtcauchydist](crtcauchydist)
  - [dropdist](dropdist)
  - [dspdbs](dspdbs)
  - [dspdistdbs](dspdistdbs)
  - [dspdistdts](dspdistdts)

* テーブル一覧  
  DataBase名:distdb  
  
  |テーブル名称              |コレクション名|
  |--------------------------|--------------|
  |標準正規分布表            |norminv       |
  |対数正規分布表            |lognorminv    |
  |T分布表                   |tinv          |
  |F分布表                   |finv          |
  |パレット分布表            |gpinv         |
  |Zipf分布表                |zipfinv       |
  |ベータ2項分布表           |bebi          |
  |階２乗分布表              |chi2inv       |
  |指数分布表                |expinv        |
  |２項分布表                |biinv         |
  |Γ分布表                  |gminv         |
  |ガンベル分布表            |guinv         |
  |超幾何分布表              |hgeinv        |
  |スミルノフ・グラブス分布表|gninv         |
  |ラプラス分布表            |lainv         |
  |レヴェ分布表              |leinv         |
  |仲上分布表                |nginv         |
  |ポイソン分布表            |poinv         |
  |トライアングル分布表      |tglinv        |
  |ワイブル分布表            |wblinv        |
  |コーシー分布表            |cauchyinv     |
