# bd-infra
A development big data infrastructure with docker-compose.
<br> In this platform, you will have  HDFS, Hive, Spark, Hue, Zeppelin, Kafka, Zookeeper, and Streamsets connected together.
<br> Just run `docker-compose up` and enjoy!
or use `stack_start.sh` to start on Docker swarm

<br> You can find more explenation in this article:

https://itnext.io/creating-a-big-data-development-platform-using-docker-compose-892f7f4da738

http://localhost:9870 - NameNode

http://localhost:9864 - DataNode

http://localhost:8888 - Hue

User/password created at first usage

http://localhost:8080 - Spark Master

http://localhost:8081 - Spark Worker 1

http://localhost:8082 - Spark Worker 2

http://localhost:19090 - Zeppelin

Default user/pass: admin/zepadmin
Users may be defined in zeppelin/conf/shiro.ini
