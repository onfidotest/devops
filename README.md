# Instructions #
Real easy;
```
docker run --name redis -d redis
docker run --name onfido -d --link redis -p 5000:5000 onfidotest/devops
```

# Test it #
* ```curl -X POST http://localhost:5000/set```
* ```curl http://localhost:5000/get```