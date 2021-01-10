## Preparing environment for Spark
1. Download and install spark compiled with hadoop, in this case Spark 3.X with Hadoop 2.7

2. Install a version of JVM 8 or higher

3. Unzip spark downloaded bins using tar -xf spark... 

4. Move spark extracted folder to /opt/spark using `mv spark.x /opt/spark`

## Setting up Spark's environment
1. Open with vim ~/.bashrc file

2. Add next configuration to file
`
export SPARK_HOME=/opt/spark
export PATH=$PATH:$SPARK_HOME/bin/:$SPARK_HOME/sbin
`

3. Enable changes with `source ~/.bashrc`

## Start Standalone Master Server
1. We need to execute next command `start-master.sh`

2. Once spark is running we can access the webUI via port 8080 `localhost:8080`


