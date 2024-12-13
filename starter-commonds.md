confluent local services start

kafka-console-producer --topic test-topic --broker-list localhost:9092  

 kafka-console-consumer  --topic test-topic --bootstrap-server localhost:9092  --from-beginning

 confluent local services stop

 confluent local destroy
