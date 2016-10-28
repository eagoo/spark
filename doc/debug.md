#maven debug
0:dev开发网设置git代理
```text
  git config --global https.proxy https://proxy.tencent.com:8080
  git config --global http.proxy http://dev-proxy.oa.com:8080
```

1.maven debug 设置执行目录为H:/git/spark/examples，设置logging file为debug
```shell
exec:java -Dscala.usejavacp=true -Dspark.master=local[*] -Dspark.logLineage=true -Dexec.mainClass=org.apache.spark.examples.SparkPi -Dexec.classpathScope=compile -Dexec.arguments=10 -Dlog4j.configuration=file:///h:/git/spark/examples/log4j-defaults.properties
```


