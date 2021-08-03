# how to build the docker image
```
docker build -t demo:1.0 .
```
# how to run the docker image
```
docker run --name demo-nginx -d -p 8080:80 demo:1.0
docker run --name demo1-nginx -d -p 8081:80 demo:1.0
```