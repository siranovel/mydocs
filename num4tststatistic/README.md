num4tststatistic
================
1. 目的

    検定統計量を計算する

1. 前提

   サポートOS: rubyが実行できるOS  
   必要ライブラリ:  ruby rake-compilerライブラリ  

1. 機能範囲

1. 機能範囲外

1. 機能制限

1. 機能詳細
    * パラメトリック検定
      - [正規母集団の母平均の検定量](populationMean.md)
      - [正規母集団の母分散の検定量](populationVar.md)
      - [母比率の検定量](populationRatio.md)
      - [2つの母平均の差の検定量(等分散性を仮定)](diffPopulationMean2EquVar.md)
      - [2つの母平均の差の検定量(不等分散性を仮定)](diffPopulationMean2UnEquVar.md)
      - [ウェルチ検定の為の自由度](df4welch.md)
      - [対応のある2つの母平均の差の検定量](diffPopulationMean.md)
      - [2つの母分散の差の検定量](diffPopulationVar.md)
      - [2つの母比率の差の検定量](diffPopulationRatio.md)
      - [ピアソン相関係数](pearsoCorrelation.md)
      - [適合度の検定量](fidelity.md)
      - [独立性の検定量](independency.md)
    * ノンパラメトリック検定
      - [マン・ホイットニーのU検定](utest.md)
      - [ウィルコクス符号付き順位検定](wilcoxontest.md)
      - [スピアマンの順位相関係数](spearmanscorr.md)
      - [ケンドールの順位相関係数](kendallscorr.md)
      - [コルモゴルフ・スミルノフ検定(2標本)](ks2test.md)
    * 外れ値検定
      - [グラプス・スミルノフの外れ値の検定量](grubbs.md)
      - [エラーバー](errbar.md)

