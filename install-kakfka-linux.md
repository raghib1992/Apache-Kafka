# Install kafka on linux
### Ref: https://www.conduktor.io/kafka/how-to-install-apache-kafka-on-linux
***
## Install Java JDK version 11


PATH="$PATH:~/kafka_2.13-3.2.0/bin"
## Start zookeeper
zookeeper-server-start.sh ~/kafka_2.13-3.2.0/config/zookeeper.properties

## Start Kafka
kafka-server-start.sh ~/kafka_2.13-3.2.0/config/server.properties

## Kafka without zookeeper
https://www.conduktor.io/kafka/how-to-install-apache-kafka-on-linux-without-zookeeper-kraft-mode

PATH="$PATH:~/kafka_2.13-3.2.0/bin

mPcbCqfASBuPiiIsoavRyA 

