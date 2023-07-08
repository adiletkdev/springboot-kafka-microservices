springboot-kafka-microservices
===================

Event-Driven Microservices architecture with patterns using Spring Boot, Kafka

## Required Software

* _Java 17_
* _Spring Boot 3.1.1_
* _Kafka_2.13-3.5.0_

## Usage

```bash
# Start the ZooKeeper service
$ bin/zookeeper-server-start.sh config/zookeeper.properties

# Start the Kafka broker service
$ bin/kafka-server-start.sh config/server.properties
```