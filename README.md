# infrastructure
docker-compose -f common.yml -f zookeeper.yml up

docker-compose -f common.yml -f kafka-cluster.yml up

docker-compose -f common.yml -f init_kafka.yml up
