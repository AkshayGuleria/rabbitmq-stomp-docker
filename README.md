# rabbitmq-stomp-docker
Dockerfile for creating RabbitMQ docker images (plugins: mgmt, stomp, web-stomp)

# build
docker build -t rabbitmq-stomp:<tag>
  
# run in container
docker run -d --hostname <host-name> --name rabbitmq-server -p 15672:15672 -p 61613:61613 -p 15671:15671 <image>
