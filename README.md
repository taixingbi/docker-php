
### run docker
```
docker-compose build
docker-compose up -d
```

http://localhost:8089/


### access container
```
docker exec -it containerId bash   
```

### more docker 
```
docker stop $(docker ps -aq)    
docker rm $(docker ps -aq)    
docker rmi $(docker images -q)
```


### reference
https://www.youtube.com/watch?v=kJaDjDRvCzE&t=111s
