# TUTORIAL 8

## Reflection

1. How many data your publlsher program will send to the message broker in one
run? 

    - Five data messages will be sent in one run. Each call to `publish_event`sends one `UserCreatedEventMessage`.


2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?

    - The URL is indeed the same in both publisher and subscriber. this means that both program are connected to the same AMQP server instances running on the local machine. They also used the same credentials to authenticate with the server and communicate over the AMQP port, enabling communication between the two components.

## Preparing Message Broker(RabbitMQ)

1. Successfully Run RabbitMQ
![Preparing RabbitMQ](/static/Screenshot1.jpg)

2. Sending and Processing Event
![Publisher](/static/Screenshot2.jpg)
![RabbitMQ](/static/Screenshot3.jpg)


