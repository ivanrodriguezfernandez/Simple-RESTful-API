### Simple-RESTful-API
Simple RESTful API in Go

### Install Package  
```
go get github.com/gorilla/mux
```

### Build Application  
```
go build main.go
```

### Run Application  
```
go run main.go
```

### Docker

Build an image from a Dockerfile
```
docker build -t simpleapi .
```
Run a command in a new container

```
docker run -it simpleapi
docker run -p 8081:8081 simpleapi
```

See docker image contents
````docker run -it simpleapi sh````
### App
http://localhost:8081/users
