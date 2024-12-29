dspdistdts
==========
コレクション内のデータ

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBInfoLib.new
ret = mongo.dspdistdts("asininv")
ret.each do |map|
    p map
end
```

* 出力サンプル

<pre>
12月 28, 2024 12:23:56 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Cluster created with settings {hosts=[localhost:27017], mode=SINGLE, requiredClusterType=UNKNOWN, serverSelectionTimeout='30000 ms', maxWaitQueueSize=500}
12月 28, 2024 12:23:56 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Cluster description not yet available. Waiting for 30000 ms before timing out
12月 28, 2024 12:23:56 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Opened connection [connectionId{localValue:1, serverValue:11}] to localhost:27017
12月 28, 2024 12:23:56 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Monitor thread successfully connected to server with description ServerDescription{address=localhost:27017, type=STANDALONE, state=CONNECTED, ok=true, version=ServerVersion{versionList=[4, 2, 9]}, minWireVersion=0, maxWireVersion=8, maxDocumentSize=16777216, logicalSessionTimeoutMinutes=30, roundTripTimeNanos=7826694}
12月 28, 2024 12:23:56 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Opened connection [connectionId{localValue:2, serverValue:12}] to localhost:27017
{"p"=>0.0, "x"=>0.0, "_id"=>"6766995e82ddfb27d50af591"}
{"p"=>0.001, "x"=>2.4673990709169446e-06, "_id"=>"6766996082ddfb27d50af592"}
{"p"=>0.002, "x"=>9.869571931435076e-06, "_id"=>"6766996082ddfb27d50af593"}
{"p"=>0.003, "x"=>2.220644552509664e-05, "_id"=>"6766996082ddfb27d50af594"}
{"p"=>0.004, "x"=>3.947789809193986e-05, "_id"=>"6766996082ddfb27d50af595"}
...
{"p"=>0.995, "x"=>0.9999383162408302, "_id"=>"6766996582ddfb27d50af974"}
{"p"=>0.996, "x"=>0.999960522101908, "_id"=>"6766996582ddfb27d50af975"}
{"p"=>0.997, "x"=>0.9999777935544749, "_id"=>"6766996582ddfb27d50af976"}
{"p"=>0.998, "x"=>0.9999901304280686, "_id"=>"6766996582ddfb27d50af977"}
{"p"=>0.999, "x"=>0.999997532600929, "_id"=>"6766996582ddfb27d50af978"}
</pre>


