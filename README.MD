# Docker image with Kafka Kraft (Kafka 2.8.0 preview feature without Zookeeper)

Docker image with Kafka in preview mode using Kraft instead of Zookeper.

Hub link: https://hub.docker.com/repository/docker/oque/kafka-kip500-kraft/general

Run with

```
docker run --name kafka -d -p 9092:9092 oque/kafka-kip500-kraft:latest
```