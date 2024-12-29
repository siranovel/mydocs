dspdbs
======
dbs情報を表示

* 使い方

```ruby
require 'num4distdb'

mongo = Num4DistDBLIB::Num4DistDBInfoLib.new
ret = mongo.dspdbs
ret.each do |name|
    puts name
end
```

* 出力サンプル

<pre>
12月 28, 2024 12:15:17 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Cluster created with settings {hosts=[localhost:27017], mode=SINGLE, requiredClusterType=UNKNOWN, serverSelectionTimeout='30000 ms', maxWaitQueueSize=500}
12月 28, 2024 12:15:17 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Cluster description not yet available. Waiting for 30000 ms before timing out
12月 28, 2024 12:15:17 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Opened connection [connectionId{localValue:1, serverValue:7}] to localhost:27017
12月 28, 2024 12:15:17 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Monitor thread successfully connected to server with description ServerDescription{address=localhost:27017, type=STANDALONE, state=CONNECTED, ok=true, version=ServerVersion{versionList=[4, 2, 9]}, minWireVersion=0, maxWireVersion=8, maxDocumentSize=16777216, logicalSessionTimeoutMinutes=30, roundTripTimeNanos=9803062}
12月 28, 2024 12:15:17 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Opened connection [connectionId{localValue:2, serverValue:8}] to localhost:27017
admin
config
distdb
local
</pre>


