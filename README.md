# docker-kafka

```
docker-compose -f docker-compose-kafka.yml up -d

docker-compose -f docker-compose-kafka.yml down

docker-compose -f docker-compose-kafka.yml ps

```

* offsets.topic.replication.factor : 기본 값은 3으로, 하나의 파티션이 총 세 개로 분산 저장되는 것
* auto.create.topics.enable : 생성되지 않은 토픽을 자동으로 생성할지 여부. 기본값은 true
* log.retention.hours : 세그먼트 파일의 삭제 주기, 기본값 hours, 168시간( 7일 )

#참고
-------
* [wurstmeister/kafka-docker](https://github.com/wurstmeister/kafka-docker)
* [docker-compose 를 사용하여 kafka Cluster 및 Kafka Manger 세팅하기](https://akageun.github.io/2020/05/01/docker-compose-kafka-cluster-manager.html)
* [apache-kafka-install-by-docker](https://daddyprogrammer.org/post/12087/apache-kafka-install-by-docker/)
