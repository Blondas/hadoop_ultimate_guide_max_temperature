1. create runnable package:
mvn package

2. executing program:
export HADOOP_CLASSPATH=target/maxTemperature-1.0-SNAPSHOT.jar
hadoop MaxTemperature input/sample.txt output
