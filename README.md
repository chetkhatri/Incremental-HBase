# Incremental-HBase
Incremental HBase POC

1. Pull this repository.
2. Go to root of this project.
3. sbt clean assembly
4. go to the target directory for getting Uber Jar
 
 /IncrementalHBase/target/scala-2.11/IncrementalHBase-assembly-1.0.jar
 
5. Execute the Spark Job
``` $SPARK_HOME/bin/spark-submit --class com.chetan.poc.hbase.IncrementalJob /home/chetan/Documents/open-contribution/IncrementalHBase/target/scala-2.11/IncrementalHBase-assembly-1.0.jar```







