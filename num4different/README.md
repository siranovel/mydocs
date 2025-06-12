num4diffrent
============
1. 目的

    数値計算によるニュートン力学の微分形式の解析的な解法

1. 前提

   サポートOS: rubyが実行できるOS  
   必要ライブラリ:  ruby ffi-compilerライブラリ  

1. 機能範囲

   ![num4diff](images/ucNumDiff.jpg)

1. 機能範囲外

1. 制限事項

1. 詳細機能
    * 一段法
        * [オイラー法](eulerMethod.md)
        * [ホイン法](heunMethod.md)
        * [ルンゲ・クッタ法](rungeKuttaMethod.md)
    * 多段法
        * [アダムス・バッシュフォース法(k段)](adamsBashforthMethod.md)
        * [アダムス・ムルトン法(k段)](adamsMoultonMethod.md)
    
