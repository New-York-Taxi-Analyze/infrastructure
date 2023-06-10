# infrastructure
docker-compose -f common.yml -f zookeeper.yml up

docker-compose -f common.yml -f kafka-cluster.yml up

docker-compose -f common.yml -f init_kafka.yml up

docker-compose -f common.yml -f akhq.yml up

# help commands
zookeeper commands:
http://localhost:8088/commands
