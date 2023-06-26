[Maintainer: Saha Merlin](https://www.linkedin.com/in/merlin-saha/)

# Kafka Architecture
![ZOOKEEPER & SCHEMA REGISTRY ARCHITECTURE](https://github.com/devsahamerlin/kafka-docker-compose/blob/main/ZOOKEEPER-SCHEMA-REGISTRY-ARCHITECTURE.png?raw=true)

# Kraft mode

```sh
cd kraft-mode

docker-compose -f common.yml -f kafka-cluster-kraft.yml up -d
```
# manage ui in kraft mode 

open brower and check 
http://localhost:9021  or  http://localhost:8089

# deploy with zookeeper
```sh
cd kafka-with-zookeeper

docker-compose -f common.yml -f zookeeper.yml up -d

docker-compose -f common.yml -f kafka_cluster.yml up -d
```
# manage ui with zookeeper

open brower and check
http://localhost:8089

# How topic flow work ?

![KAFKA ARCHITECTURE](https://github.com/devsahamerlin/kafka-docker-compose/blob/main/KAFKA-ARCHITECTURE.png?raw=true)
