PoissonRegAna
=============
ポアソン回帰分析

## 概要
### 非線形回帰分析の場合

稀にしか起こらない現象に関するカウントデータを分析するための手法。  
カウントデータ：一定期間内にある現象が起こった回数を数え上げたデータ  

### AIC(赤池の情報基準)の場合

モデルの当てはまり度を表す統計量。  
値が小さいほど当てはまりがいいとされますが、相対的な評価として用いられるため、  
「○以下であることが望ましい」というような基準はありません。

## 使い方
### ポアソン回帰分析の場合

```ruby
glsyi = [4, 10, 7, 14]
glsxij = [
    [1],
    [2],
    [3],
    [4],
]
regana = Num4RegAnaLib::PoissonRegAnaLib.new
regana.non_line_reg_ana(glsyi, glsxij)
```

### AIC(赤池の情報基準)の場合

```ruby
reg = {
     :intercept => 1.3138,    # 定数項
     :slope    =>  [0.3173],  # 回帰係数
}
xij = [
    [1],
    [2],
    [3],
    [4],
]
regana = Num4RegAnaLib::PoissonRegAnaLib.new
regana.get_aic(reg, xij)
```


