# Beamery-DevOps-Challenge

Please, choose one of the two options to complete:
  
  1- Run a Mongo instance using Docker. Write a simple command line tool that will create a collection in Mongo (schema of your choice), populate it with some fake data, and create custom indexes for the collection. 
  Please, use https://github.com/globalsign/mgo library.
  
  2- Run a Kafka instance using Docker. Write a command line that is able to send a message to a Kafka topic and also fetch a message from another topic 
  Please use https://github.com/Shopify/sarama library
  
  Example:

```$ kafka-cli --topic "Green" --send "My message"
$ kafka-cli --topic "Green" --read
Message```
