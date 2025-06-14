propensity_score
================
傾向スコアによる効果検証

* 使い方

前処理  
  demo-ps.csvのファイルを読み込み、目的変数(yi)、共変量(xij)、介入変数(zi)を設定する

傾向スコアマッチング(PSM:Propensity Score Matching)による効果検証の場合

```ruby
regana = Num4RegAnaLib::RCTLib.new
regana.psm(yi, xij, zi)
```

逆確率重み付け推定(IPW:Inverse Probability Weighting)による効果検証の場合

```ruby
regana = Num4RegAnaLib::RCTLib.new
regana.ipw(yi, xij, zi)
```





