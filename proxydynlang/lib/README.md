# 概要 #
c言語から動的言語(perl,python,ruby等)のプログラムの中の関数およびメゾットを呼び出すインターフェースを提供です。


# 提供している機能 #
## 基本機能 ##
* init:  
    動的言語の初期化
* dynFileParse:  
    動的言語ファイルのコンパイル
* funccall:   
    動的ファイル内の関数を実行
* classStaticMethodCall:  
    スタティックメゾッドを実行
* getInstance:  
    クラスのインスタンスを生成
* classObjectMethodCall:  
    インスタンスに対するメゾッドを実行
* end:  
    動的言語の終了
## スレッド機能 ##
* create:  
    スレッド生成
* creates:  
    複数スレッド生成
* join:  
    スレッド終了待ち
* joins:  
    複数スレッド終了待ち
* ThreadFuncParamFactory:  
    スレッドに渡すパラメータ構造体(基本機能使用時)の生成
# パラメータおよび戻り値 #
## パラメータ ##
動的言語内の関数およびメゾッドに渡すパラメータは、以下の種類です。
* int型
* long型
* float型
* double型
* 文字列型
* int型の配列
* long型の配列
* float型の配列
* double型の配列
* ハッシュ型  
  key：文字列型のみ  
  value: key毎に型指定  

* オブジェクト型  

## 戻り値 ##
動的言語内の関数およびメゾッドの戻り値は、以下の種類です。
* 戻り値なし
* int型
* long型
* float型
* double型
* 文字列型
* int型の配列
* long型の配列
* float型の配列
* double型の配列
* ハッシュ型  
  key：文字列型のみ
  value: key毎に型指定

* ハッシュの配列
* オブジェクト型  
　ラムダ式：無名関数
  version 2.1以降対応



