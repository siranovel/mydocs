num4normality
================
1. 目的

    正規性の検定をする

1. 前提

   サポートOS: rubyが実行できるOS  
   必要ライブラリ:  ruby rake-compilerライブラリ  

1. 機能範囲

1. 機能範囲外

1. 機能制限

1. 機能詳細

    * プロット
      - [Q-Qプロット](qqplot.md)
      - [コルモゴルフ・スミルノフ検定プロット](ksplot.md)
      - [Q-Q and KS検定プロット](qqksplot.md)
      - [P-Pプロット](ppplot.md)
      - [P-P and KS検定プロット](ppksplot.md)

|検定方法(両側検定のみ)                    |N範囲(サンプルサイズ|
|-----------------------------------------|------------------|
|[Kolmogorov-Smirnov]((kstest.md)         |N<100             |
|Lillefors                                |4<N≦100,2000≦N  |
|[Anderson-Darling](adtest.md)            |5000≦N           |
|[タコスディーノ検定(歪度)](skewnesstest.md)|4≦N              |
|[タコスディーノ検定(尖度)](kurtosistest.md)|4≦N              |
|[オムニバス検定](omnibustest.md)          |4≦N              |
|Shapiro-Wilk                             |3≦N≦5000        |
|Chen-Shapiro                             |10≦N≦2000       |
|[Jarque-Bera検定](jbtest.md)             |                  |

注意：
サンプルサイズの要件のみお満たすというだけでは、テスト結果が効率的かつ協力であることを保証するものではありません。殆ど全ての正規性検定の手法において、小さいサンプルサイズ(30以下)では不十分です。


