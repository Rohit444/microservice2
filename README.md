# microservice2
This is a Spring Boot microservice using Apache camel is receiveing messages from an Active Mq and printing received messages on console.
We are also representing here how Apcahe camel help us to integrate differnet componenets very easily.

Below is the Docker command to start a docker instance of Active MQ:

docker run -p 61616:61616 -p 8161:8161 rmohr/activemq

Below is the ActiveMQ WebConsole Url:

http://0.0.0.0:8161/
