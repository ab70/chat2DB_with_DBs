# chat2DB_with_DBs


## check the docker network bridge to get host ip
```
sudo docker network inspect chatdb-network
```

then add Gateway ip to that host so it can access


As for now, its can be accesed using username, pass with host: "container name"