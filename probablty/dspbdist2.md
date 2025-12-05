大数の弱法則
===========
ベルヌーイ試行による確率をグラフ表示する

# 概要

標本nが十分に大きければ、「独立に同一の分布に従う確率変数」の標本平均と母平均とのズレが一定の値を超える確率が0である  

言い換えると、サンプルが大きくなれば、標本平均は母平均に近づいていくという事  
(数学的には、標本平均は母平均に確率収束すると言います。)  

```math
\lim_{n\to \infty} P \{ | \bar{x_n} - \mu | \geq \epsilon \} = 0
```

* 表示項目
  - 平均:0.4 標準偏差:0.05
  - 平均:0.4 標準偏差:0.03
  - 平均:0.4 標準偏差:0.01

## 使い方

```ruby
require 'num4probstdy'
Num4ProbStdyLib.dspbdist2(n=1200)
```

## 出力サンプル

```ruby
require 'num4probstdy'
Num4ProbStdyLib.dspbdist2(n)
```

![dspbdist2](images/weekLawOfLargeNums.jpg)


