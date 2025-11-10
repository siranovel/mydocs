num4tststatistic2
=================
1. 目的

    統計的仮説検定(num4tststatistic & num4hypothtstの統合)

1. 前提

   サポートOS: rubyが実行できるOS  
   必要ライブラリ:  num4tststatisticライブラリ  
                   num4hypottstライブラリ  

1. 機能範囲

1. 機能範囲外

1. 機能制限

1. 機能詳細
    * [パラメトリック検定](parametric.md)
      - [正規母集団の母平均の検定](populationMean.md)
      - [正規母集団の母分散の検定](populationVar.md)
      - [母比率の検定](populationRatio.md)
      - [2つの母平均の差の検定(等分散性check有り)](diffPopulationVarMean.md)
      - [2つの母平均の差の検定(等分散性を仮定)](diffPopulationMean2EquVar.md)
      - [2つの母平均の差の検定(不等分散性を仮定)](diffPopulationMean2UnEquVar.md)
      - [対応のある2つの母平均の差の検定](diffPopulationMean.md)
      - [2つの母分散の差の検定(等分散性)](diffPopulationVar.md)
      - [2つの母比率の差の検定](diffPopulationRatio.md)
      - [適合度の検定量](fidelity.md)
      - [独立性の検定量](independency.md)
    * [ノンパラメトリック検定](nonparametoric.md)
      - [マン・ホイットニーのU検定](utest.md)
      - [ウィルコクス符号付き順位検定](wilcoxontest.md)
      - [コルモゴルフ・スミルノフ検定(2標本)](ks2test.md)
    * [外れ値検定](outlier.md)
      - [グラプス・スミルノフの外れ値の検定量](grubbs.md)
      - [エラーバー出力](errbar.md)
    * [相関係数検定](corre.md)
      * [無相関検定](no_corre.md)
        - [ピアソン相関係数](pearsoCorrelation.md)
        - [スピアマンの順位相関係数](spearmanscorr.md)
        - [ケンドールの順位相関係数](kendallscorr.md)
      * [母相関係数の検定](popu_corre.md)
        - [ピアソン相関係数](pearsoCorrelation.md)
        - [スピアマンの順位相関係数](spearmanscorr.md)
        - [ケンドールの順位相関係数](kendallscorr.md)
      * [差の母相関係数の検定](diff_popu_corre.md)
        - [ピアソン相関係数](pearsoCorrelation.md)
        - [スピアマンの順位相関係数](spearmanscorr.md)
        - [ケンドールの順位相関係数](kendallscorr.md)


