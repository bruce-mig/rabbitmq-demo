# rabbitmq-demo

A simple demo with `RabbitMQ`.  

-To start Docker container.  

 `docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.13-management`

-In a terminal, run the publisher:

 `make publisher`

-Then, run the consumer:

 `make consumer`