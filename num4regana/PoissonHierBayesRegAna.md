PoissonHierBayesRegAna
======================
ポアソン回帰分析

## 概要
### 非線形回帰分析の場合

データの複雑な構造を扱う為の統計手法。  
特に、異なるレベルでデータが相互に関連している場合、その特徴を効果的に捉えることができる。  
このモデルは、データのばらつきや不確実性を自然に表現することができ、実際の問題に対する柔軟なアプローチになる。  

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
regana = Num4RegAnaLib::HierBayesPoissonRegAnaLib.new
regana.non_line_reg_ana(glsyi, glsxij)
```

