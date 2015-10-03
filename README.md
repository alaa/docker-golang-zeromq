# docker-golang-zeromq
Docker file for ZeroMQ with Golang

## Usage:

```
docker pull alaa/go-zmq

docker run -d \
           -P \
           --name my-service \
           -v $(pwd)/app:/app \
           alaa/go-zmq \
           go run /app/main.go
```
