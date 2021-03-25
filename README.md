# RabbitMQ example with Go

1. Run Docker.
2. Execute in Terminal: `docker run -d --hostname rabbitmq-example --name rabbitmq -p 15672:15672 -p 5672:5672 rabbitmq:3-management`
2. Run the consumer service: `go run go-rabbitmq-example/consumer/main.go`
3. Run the main program and send a basic request: `go run go-rabbitmq-example/main.go`
