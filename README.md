# Kafka-Practice
Spring Boot + Kafka (Produce &amp; Consume) Application

## Follow the below steps to run the Kafka with zookeeper

``` .\bin\windows\kafka-server-start.bat .\config\server.properties ```

``` .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties ```

## Command to create kafka topic
``` .\bin\windows\kafka-topics.bat --create --topic test-topic --bootstrap-server localhost:9092 --replication-factor 1 --partitions 4 ```

## Command to list all topics in kafka broker
``` .\bin\windows\kafka-topics.bat --list --bootstrap-server localhost:9092 ```
