# infrastructure
docker-compose -f common.yml -f kafka-cluster.yml up

docker-compose -f common.yml -f kafka-topic.yml up

# help commands
zookeeper commands:
http://localhost:8088/commands
