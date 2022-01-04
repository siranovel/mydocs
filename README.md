mydocs
======
自作品物のドキュメント資料です。

## Description ##
７つのオブジェクト指向設計の基本原則について、C言語で作成しています。  

- オブジェクト指向設計の基本原則  
  - 単一責任の原則(Single Responsibility Principle)
  - オープン・クローズドの原則(Open-Closed Principle)
  - リスコフの置換原則（Liskov Substitution Principle)
  - インターフェース分離の法則(Interface Segregation Principle)
  - 依存関係逆転の原則(Dependency Inversion Principle)
  - DRY(Don't repeat yourself)の原則
  - KISS(Keep It Simple Stupid)の原則

## リポジトリ一覧 ##

|repository                            |内容                                                                                   |
|--------------------------------------|---------------------------------------------------------------------------------------|
|[libproxydynlang](proxydynlang/lib)   |C言語から動的プログラム(perl,python,ruby,lua等)内の関数及びメゾッドの呼び出しライブラリ|
|[proxydynlangtest](proxydynlang/test) |libproxydynlangのtestプログラム                                                        |
|[libproxyjni](proxyjni/lib)           |C言語からjavaクラス内のメゾッドの呼び出しライブラリ                                    |
|[proxyjnitest](proxyjni/test)         |libproxyjniのtestプログラム                                                            |
|jniscrteng                            |javaのScriptEngineを利用して、動的プログラム(jruby,jython3,graaljs等)内の関数及びメゾッドの呼び出しライブラリ|
|[mongodbtool](mongodbtool/)           |mongoDBに、commons-math3を利用して、分布表のデータをmongodbに格納ツール。              |
|[distgraph](distgraph/)               |commons-math3を利用して、各分布のグラフを表示するプログラム                            |
|[javatool](javatool/)                 |c言語からJNIライブラリを使用したツール集                                               |
|[luatool](luatool/)                   |c言語からluaのライブラリを使用したツール集                                             |
|[pythontool](pythontool/)             |c言語からpythonのライブラリを使用したツール集                                          |
|[rubytool](rubytool/)                 |c言語からrubyのライブラリを使用したツール集                                            |
|[probality](probablty/)               |確率・統計の勉強用                                                                     |


## Download手順 ##

各リポジトリの取得方法  
    git clone https://github.com/siranovel/リポジトリ.git  
例  
　　jniscrtengの場合  
    git clone https://github.com/siranovel/jniscrteng.git  

