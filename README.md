# Instructions #
Real easy;
```
docker run --name redis -d redis
docker run --name onfido -d --link redis -p 5000:5000 onfidotest/devops
```
