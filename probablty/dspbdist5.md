マルチンゲール
=============
マルチンゲール性を、グラフ表示する

## 概要

以下の要件をもつ確率過程を、「マルチンゲール」と呼ぶ。  
ただし、Yは整数値をとる確率変数(あるいは確率ベクトル)であるとします。  
$ E[Y_{n}|Y_{n-1}, \cdots Y_{0}]=Y_{n-1} $

時点n-1における時点nのYの条件付き期待値(上の式)は、時点n-1のYと同様に確からしいということ


* 表示項目
  - 0.45
  - 0.50
  - 0.55

## 出力サンプル
### 回数設定あり

```ruby
require 'num4probstdy'
Num4ProbStdyLib.dspbdist5(n=600)
```

### 回数設定なし

```ruby
require 'num4probstdy'
Num4ProbStdyLib.dspbdist5()
```
![dspbdist5](images/martine.jpg)

