populationVar
=============
正規母集団の母分散の検定量

* 使い方

```ruby
xi = xi = [35.2, 34.5, 34.9, 35.2, 34.8, 35.1, 34.9, 35.2, 34.9, 34.8]
sd = 0.4
paraTest = Num4TstStatisticLib::ParametrixTestLib.new
paraTest.populationVar(xi, sd*sd)
```

