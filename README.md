mydocs
======
自作品物のドキュメント資料です。

## Description ##
７つのオブジェクト指向設計の基本原則に基づいて、C色んなライブラリを作成しています。  

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
|[jniscrteng](jniscrteng)              |javaのScriptEngineを利用して、動的プログラム(jruby,jython3,graaljs等)内の関数及びメゾッドの呼び出しライブラリ|
|[mongodbtool](mongodbtool/)           |mongoDBに、commons-math3を利用して、分布表のデータをmongodbに格納ツール。              |
|[distgraph](distgraph/)               |commons-math3を利用して、各分布のグラフを表示するプログラム                            |
|[javatool](javatool/)                 |c言語からJNIライブラリを使用したツール集                                               |
|[luatool](luatool/)                   |c言語からluaのライブラリを使用したツール集                                             |
|[pythontool](pythontool/)             |c言語からpythonのライブラリを使用したツール集                                          |
|[rubytool](rubytool/)                 |c言語からrubyのライブラリを使用したツール集                                            |
|[probality](probablty/)               |確率・統計の勉強用                                                                     |
|[num4different](num4different)        |数値計算による常微分方程式の解析的な解法集                                                       |
|[num4equation](num4equation)          |数値計算による方程式の解析的な解法集                                                       |
|[num4integral](num4integral)          |数値計算による数値積分の解法 |
|[num4simdifferent](num4simdifferent)  |数値計算による連立常微分方程式の解析的な解法 |
|[num4partialdifferent](num4partidifferent)     |数値計算による偏微分方程式の解析的な解法 |
|[num4mechaequation](num4phyequation/num4mechaequation) |数値計算によるニュートン力学の微分形式の解析的な解法     |
|[helloci](helloci)                    |circleciによるtest&deploy|
|[stdy4act](stdy4act)                  |call to java from jruby |
|[num4hypothtst](num4hypothtst)        |統計的仮設検定のためのライブラリ |
|[num4tststatistic](num4tststatistic)  |検定統計量の計算 |
|[num4normality](num4normality)        |正規性の検定|
|[num4anova](num4anova)                |分散分析|
|[num4tststatistic2](num4tststatistic2)|統計的仮説検定(num4tststatistic & num4hypothtstの統合)|
|[num4difftest](num4difftest)          |母平均の差の検定 |
|[num4regana](num4regana)          |数値計算による回帰分析を行う |
|[num4saleana](num4saleana)          |数値計算による販売分析 |

## Download手順 ##

各リポジトリの取得方法  
    git clone https://github.com/siranovel/リポジトリ.git  
例  
　　jniscrtengの場合  
    git clone https://github.com/siranovel/jniscrteng.git  



