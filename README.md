# Spring Cloud Stream Sandbox
Spring Cloud Stream Example.

## RabbitMQ Startup
A RabbitMQ broker with default setup is required to run and test the example. The easiest way to startup a broker
for local testing is through RabbitMQ's public Docker images. Use the following command to startup the broker with
access to the management panel (http://localhost:15672/) for inspection of the exchanges and channels.

`docker run -it --rm -p 15672:15672 -p 5672:5672 rabbitmq:3-management`

