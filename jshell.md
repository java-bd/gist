## [Use External Jars in JShell](https://howtoprogram.xyz/2017/12/31/java-9-jshell-import-external-library/)
```sh
/env --class-path ~/app/java/jars/commons-pool2-2.6.0.jar:~/app/java/jars/jedis-2.9.0.jar:~/app/java/jars/log4j-1.2.17.jar:~/app/java/jars/mysql-connector-java-8.0.12.jar:~/app/java/jars/redisson-3.8.2.jar
```
## Start Jshell With External Jars
```sh
jshell --class-path ~/app/java/jars/commons-pool2-2.6.0.jar:~/app/java/jars/jedis-2.9.0.jar:~/app/java/jars/log4j-1.2.17.jar:~/app/java/jars/mysql-connector-java-8.0.12.jar:~/app/java/jars/redisson-3.8.2.jar
```
