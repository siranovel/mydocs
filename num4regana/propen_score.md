propensity_score
================
傾向スコアによる効果検証

## 概要
### 傾向スコアマッチング(PSM)

処理群に属するそれぞれの人に、共変量の値が同じ人、あるいは近い人を、対照群の中から選ぶという「マッチング」の操作を行う。

### 逆確率重み付け推定(IPW)

対照群の一人ひとりに「重み(weight)」を定義します。この重みは、共変量の値を基にした、「その個人を何人分(何倍)として扱うか」という数字です。対照群の結果は、単純な平均ではなく重みを考慮した「重み付き」平均を計算し、それを処理群の平均と比較することで、共変量の違いを除いた効果を算出します。

## 使い方
### 傾向スコアマッチング(PSM:Propensity Score Matching)による効果検証の場合

```ruby
regana = Num4RegAnaLib::RCTLib.new
regana.psm(yi, xij, zi)
```

### 逆確率重み付け推定(IPW:Inverse Probability Weighting)による効果検証の場合

```ruby
regana = Num4RegAnaLib::RCTLib.new
regana.ipw(yi, xij, zi)
```





