sudo docker run -d --rm --name rabbitmq -p 15672:15672 -p 5672:5672 rabbitmq:3.7-management

curl -d "path=*" http://localhost:8888/monitor
