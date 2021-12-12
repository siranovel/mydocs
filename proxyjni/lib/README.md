# 概要 #
c言語からJNI(Java Native Interface)を利用して、Javaプログラム中のメゾットを呼び出すインターフェースを提供です。
c言語で、オブジェクト指向風に作成しています。

# 提供している機能 #
## 基本機能 ##
* init:  
    JNI(Java Native Interface)の初期化
* classStaticMethodCall:  
    スタティックメゾッドを実行
* getInstance:  
    クラスのインスタンスを生成
* classObjectMethodCall:  
    インスタンスに対するメゾッドを実行
* end:  
    JNIの終了
## 拡張 ##
* SetClasPath  
  ClasPath設定  
* SetSysProp  
  Systemプロパティ設定  
* GetSysProp  
  Systemプロパティ取得

# パラメータおよび戻り値 #
## パラメータ ##
java内の関数およびメゾッドに渡すパラメータは、以下の種類です。
* int型
* long型
* float型
* double型
* 文字列型
* int型の配列
* long型の配列
* float型の配列
* double型の配列
* オブジェクト型の配列  
  (ver 2.1.5以降対応)
* ハッシュ
* オブジェクト型

## 戻り値 ##
java内の関数およびメゾッドの戻り値は、以下の種類です。
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
* ハッシュ
* ハッシュの配列
* オブジェクト型  
    ラムダ式：無名関数



