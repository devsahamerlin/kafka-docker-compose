# Kraft mode

cd kraft-mode

docker-compose -f common.yml -f kafka-cluster-kraft.yml up -d

# manage ui in kraft mode 

open brower and check 
http://localhost:9021  or  http://localhost:8089

# deploy with zookeeper

cd kafka-with-zookeeper

docker-compose -f common.yml -f zookeeper.yml up -d

docker-compose -f common.yml -f kafka_cluster.yml up -d

# manage ui with zookeeper

open brower and check
http://localhost:8089# kafka-docker-compose
