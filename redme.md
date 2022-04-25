
./bin/windows/kafka-topics.bat --create --topic transaction --bootstrap-server localhost:9092

./bin/windows/kafka-topics.bat --describe --topic transaction --bootstrap-server localhost:9092

./bin/windows/kafka-console-producer.bat --topic transaction --bootstrap-server localhost:9092
8
5
3
4

./bin/windows/kafka-console-consumer.bat --topic transaction --from-beginning --bootstrap-server localhost:9092
cd