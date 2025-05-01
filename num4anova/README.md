num4anova
===========
1. 目的

    数値計算による分散分析を行う

1. 前提

   サポートOS: rubyが実行できるOS  
   必要ライブラリ:  ruby rake-compilerライブラリ  

1. 機能範囲

1. 機能範囲外

1. 機能制限

1. 機能詳細
    * 多重比較
      * パラメトリック検定
        - [turkeyの方法による多重比較](turkey_test.md)
        - [ボンフェロー二の不等式による多重比較(T検定)](bonferrono_test.md)
        - [Dunnet検定](dunnet_test.md)
          - 両側検定
          - 左側検定
          - 右側検定
      * ノンパラメトリック検定
        - [ボンフェロー二の不等式による多重比較(U検定)](bonferrono_test.md)
    * 分散分析
      * 一元配置の分散分析
        - [箱ひげ図](boxWhiskerPlot.md)
        - [一元散布図](oneway_scatter_plot.md)
        - [一元配置分散分析](oneway_anova.md)
        - [バートレット検定](bartlet.md)
        - [反復測定図](replicate_plot.md)
        - [反復測定検定](replicate_test.md)
        - [クラスカル・ウォリスの検定](kruskalwallis_test.md)
      * 二元配置の分散分析
        - [二次元分散分析(繰り返し数が等しい時)](twoway_anova.md)
        - [二次元分散分析(繰り返しなし)](twoway2_anova.md)
        - [フリードマン検定](friedman_test.md)
        - [1元配置用データ作成](create_oneway.md)
      * 共分散分析
        - [回帰直線の平行性の検定](parallel_test.md)
        - [回帰直線の有意性検定](significance_test.md)
        - [水準間の差の検定](difference_test.md)
        - [区間推定](interval_estim.md)


