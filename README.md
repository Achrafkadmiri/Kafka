## Lancer le serveur Zookeeper :
start bin\windows\zookeeper-server-start.bat config/zookeeper.properties
## Lancer le Boker KAFKA :
start bin\windows\kafka-server-start.bat config/server.properties
## Lancer Kafka-console-consumer
start bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R4 --property print.key=true --property print.value=true --property key.deserializer=org.apache.kafka.common.serialization.StringDeserializer --property value.deserializer=org.apache.kafka.common.serialization.StringDeserializer
## Lancer kafka-console-producer
start bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic R4

# Une application Web qui permet d'afficher les résultats du Stream Data Analytics en temps réel

![Opera Snapshot_2024-01-27_203259_localhost](https://github.com/Achrafkadmiri/Kafka/assets/95657794/4adf4918-90c0-43e4-8109-936f580a3e99)

# Analytics
![5555555555555](https://github.com/Achrafkadmiri/Kafka/assets/95657794/8f09f589-34d2-42f1-bd29-8d496fe0335d)
