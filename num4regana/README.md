num4regana
==========
1. 目的

    数値計算による回帰分析を行う

1. 前提

   サポートOS: rubyが実行できるOS  
   必要ライブラリ:  ruby rake-compilerライブラリ  

1. 機能範囲

1. 機能範囲外

1. 機能制限

1. 機能詳細
    * 回帰分析
      * 線形回帰分析
        - [単回帰分析](SmplRegAna.md)
          - 単回帰分析
          - 決定係数
          - 相関係数
        - [重回帰分析(最小２乗法:等分散性checkあり)](OLSMultRegAna.md)
          - 重回帰分析
          - 決定係数
          - 自由度調整済み決定係数
          - VIF(Variance Inflation Factor)
          - AIC(赤池の情報基準)
      * 一般化線形回帰分析
        - [(2項)ロジスティック回帰分析](LogitRegAna.md)
          - 非線形回帰分析
          - AIC(赤池の情報基準)
        - [ポアソン回帰分析](PoissonRegAna.md)
          - 非線形回帰分析
          - AIC(赤池の情報基準)
        - [プロビット回帰分析](ProBitRegAna.md)
          - 非線形回帰分析
          - AIC(赤池の情報基準)
      * 一般化線形混合モデル
        - [(2項)ベイズロジスティック回帰分析](LogitBayesRegAna.md)
          - 非線形回帰分析
          - BIC(ベイズ情報基準)
        - [ベイズポアソン回帰分析](PoissonBayesRegAna.md)
          - 非線形回帰分析
          - BIC(ベイズ情報基準)
      * 階層ベイズモデル
        - [ポアソン回帰分析](PoissonHierBayesRegAna.md)
          - 非線形回帰分析
      * 効果検証
        - [単回帰による効果推定](smple_line_reg_ana.md)
        - 傾向スコアによる効果推定
          - 傾向スコアマッチング(PSM)
          - 逆確率重み付け推定(IPW)
