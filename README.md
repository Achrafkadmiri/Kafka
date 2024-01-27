## Lancer le serveur Zookeeper :
start bin\windows\zookeeper-server-start.bat config/zookeeper.properties
## Lancer le Boker KAFKA :
start bin\windows\kafka-server-start.bat config/server.properties
## Lancer Kafka-console-consumer
start bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R4 --property print.key=true --property print.value=true --property key.deserializer=org.apache.kafka.common.serialization.StringDeserializer --property value.deserializer=org.apache.kafka.common.serialization.StringDeserializer
## Lancer kafka-console-producer
start bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic R4
