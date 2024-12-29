dspdistdbs
==========
distdb内のテーブル一覧を表示

* 使い方

```ruby
mongo = Num4DistDBLIB::Num4DistDBInfoLib.new
ret = mongo.dspdistdbs
ret.each do |name|
    puts name
end
```

* 出力サンプル

<pre>
12月 28, 2024 12:19:17 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Cluster created with settings {hosts=[localhost:27017], mode=SINGLE, requiredClusterType=UNKNOWN, serverSelectionTimeout='30000 ms', maxWaitQueueSize=500}
12月 28, 2024 12:19:18 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Cluster description not yet available. Waiting for 30000 ms before timing out
12月 28, 2024 12:19:18 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Opened connection [connectionId{localValue:1, serverValue:9}] to localhost:27017
12月 28, 2024 12:19:18 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Monitor thread successfully connected to server with description ServerDescription{address=localhost:27017, type=STANDALONE, state=CONNECTED, ok=true, version=ServerVersion{versionList=[4, 2, 9]}, minWireVersion=0, maxWireVersion=8, maxDocumentSize=16777216, logicalSessionTimeoutMinutes=30, roundTripTimeNanos=6101963}
12月 28, 2024 12:19:18 午後 com.mongodb.diagnostics.logging.JULLogger log
情報: Opened connection [connectionId{localValue:2, serverValue:10}] to localhost:27017
gpinv
wblinv
poinv
expinv
nginv
hgeinv
biinv
loginv
chi2inv
gninv
cauchyinv
zipfinv
leinv
gminv
norminv
guinv
tglinv
lainv
lognorminv
finv
asininv
tinv
bebi
</pre>

