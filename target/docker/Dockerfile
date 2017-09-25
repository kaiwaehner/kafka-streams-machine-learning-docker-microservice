FROM java:8
MAINTAINER Kai Waehner (kontakt@kai-waehner.de, @KaiWaehner)
ADD /opt/kafka-streams-h2o-docker-microservice-1.0-SNAPSHOT-jar-with-dependencies.jar /opt/
ENTRYPOINT ["java -cp /opt/kafka-streams-h2o-docker-microservice-1.0-SNAPSHOT-jar-with-dependencies.jar com.github.megachucky.kafka.streams.machinelearning.Kafka_Streams_MachineLearning_H2O_GBM_Example"]
