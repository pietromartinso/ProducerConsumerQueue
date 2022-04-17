# Qeues example in C Sharp: Producer/consumer Hello World tutorial by RabbitMQ

1) `cd C:\Program Files\RabbitMQ Server\rabbitmq_server-3.9.15\sbin`


2) `rabbitmq-service stop` \[could use rabbitmq-server as well] 
3) `rabbitmq-service start` \[could use rabbitmq-server as well] 

4) `rabbitmqctl status` \[command line tool]

5) `rabbitmq-plugins enable rabbitmq_management` \[allow web interface]
6) `rabbitmqctl status`

- Output: "Interface: \[::], port: 15672, protocol: http, purpose: HTTP API"
- Connect to localhost:15672, login + pw = guest + guest