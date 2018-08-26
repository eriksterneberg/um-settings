% KAFKA(shell) Um Pages | Um Pages
% 
% August 23, 2018
# NAME
kafka --

# SYNOPSIS


# DESCRIPTION
./bin/kafka-console-producer.sh --broker-list 127.0.0.1:9092 --topic data.event
: Send a message on 127.0.0.1:9092

./bin/kafka-console-consumer.sh --bootstrap-server 0.0.0.0:9092 --topic data.event
: Consume a message on 127.0.0.1:9092. Add --from-beginning to get all messages.


# OPTIONS

