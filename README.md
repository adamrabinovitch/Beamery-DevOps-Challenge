# Beamery-DevOps-Challenge Part 2

This is a coding challenge. Please, choose one of the two options to complete using Golang language. When you are done add the code to your own Github/Gitlab repos for the team to review.

Options:
  
  A- Run a Mongo instance using Docker. Then write a simple command line tool that will create a collection in Mongo (schema of your choice), populate it with some fake data, and create custom indexes for the collection. 
  Please, use https://github.com/globalsign/mgo library.
  
  B- Run a Kafka instance using Docker. Then write a command line that is able to send a message to a Kafka topic and also fetch a message from another topic 
  Please use https://github.com/Shopify/sarama library.
  
  Example:

```
$ kafka-cli --topic "Green" --send "My message"
$ kafka-cli --topic "Green" --read
My Message
```

Note: we will valorate positively and good code structure and tests.

Add documentation on the README explaining how to execute your code. Include how to run Mongo or Kafka (depending on the option you choose).
