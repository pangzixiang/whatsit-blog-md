# How to use ZGC for JVM(jdk17)
##### Last updated: 2022-04-25
***
+ follow below command to startup ur java application:
```shell
java -jar -XX:+UseZGC -Xlog:gc:log/gc.log:time:filecount=5:filesize=10m -Xmx256m *.jar
```
##### note:
+ -Xmx256m is to setup the max heap size
+ -Xlog:gc:xxx is to output the gc log
***
