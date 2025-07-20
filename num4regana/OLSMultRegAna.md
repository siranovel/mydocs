OLSMultRegAna
-------------
重回帰分析(最小２乗法:等分散性checkあり)

## 使い方
### 重回帰分析の場合

```ruby
olsyi = [45, 38, 41, 34, 59, 47, 35, 43, 54, 52]
olsxij = [
    [17.5, 30],
    [17.0, 25],
    [18.5, 20],
    [16.0, 30],
    [19.0, 45],
    [19.5, 35],
    [16.0, 25],
    [18.0, 35],
    [19.0, 35],
    [19.5, 40],
]
regana = Num4RegAnaLib::OLSMultRegAnaLib.new
regana.line_reg_ana(olsyi, olsxij)
```

### 決定係数の場合

```ruby
olsyi = [45, 38, 41, 34, 59, 47, 35, 43, 54, 52]
olsxij = [
    [17.5, 30],
    [17.0, 25],
    [18.5, 20],
    [16.0, 30],
    [19.0, 45],
    [19.5, 35],
    [16.0, 25],
    [18.0, 35],
    [19.0, 35],
    [19.5, 40],
]
regana = Num4RegAnaLib::OLSMultRegAnaLib.new
regana.getr2(olsyi, olsxij)
```

### 自由度調整済み決定係数の場合

```ruby
olsyi = [45, 38, 41, 34, 59, 47, 35, 43, 54, 52]
olsxij = [
    [17.5, 30],
    [17.0, 25],
    [18.5, 20],
    [16.0, 30],
    [19.0, 45],
    [19.5, 35],
    [16.0, 25],
    [18.0, 35],
    [19.0, 35],
    [19.5, 40],
]
regana = Num4RegAnaLib::OLSMultRegAnaLib.new
regana.getadjr2(olsyi, olsxij)
```

### VIF(Variance Inflation Factor)の場合

```ruby
olsxij = [
    [17.5, 30],
    [17.0, 25],
    [18.5, 20],
    [16.0, 30],
    [19.0, 45],
    [19.5, 35],
    [16.0, 25],
    [18.0, 35],
    [19.0, 35],
    [19.5, 40],
]
regana = Num4RegAnaLib::OLSMultRegAnaLib.new
regana.getvif(olsxij)
```

### AIC(赤池の情報基準)の場合

```ruby
        #   olsyi = [45, 38, 41, 34, 59, 47, 35, 43, 54, 52]
        #   olsxij = [
        #       [17.5, 30],
        #       [17.0, 25],
        #       [18.5, 20],
        #       [16.0, 30],
        #       [19.0, 45],
        #       [19.5, 35],
        #       [16.0, 25],
        #       [18.0, 35],
        #       [19.0, 35],
        #       [19.5, 40],
        #   ]
        #   regana = Num4RegAnaLib::OLSMultRegAnaLib.new
        #   regana.getaic(olsyi, olsxij)
```





