ks2test
=======
コルモゴルフ・スミルノフ検定統計量(2標本)を計算

## 統計的検定
### 検定の手順2

対応の無い２標本の確率分布の差を計算する  
ただし、N1+N2-2のt分布に従うに従う  
(num4hypothtstを使用して棄却域に入っているかどうか判定する)

## 使い方

```ruby
xi1 = [165, 130, 182, 178, 194, 206, 160, 122, 212, 165, 247, 195]
xi2 = [180, 180, 235, 270, 240, 285, 164, 152]
nonParaTest = Num4TstStatisticLib::NonParametrixTestLib.new
nonParaTest.ks2test(xi1, xi2, 0.05)
```

