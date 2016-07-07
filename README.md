# Store useful docker commands

General
-----

List the runing containers
```
docker ps -a
```

Remove container
```
docker rm -f container_name 
```

# start a postgres server
docker run -p 5432:5432 --name postgres-db -d postgres:latest

Explanation:
------

```
-p: port forwarding between the host and the container
--name: name of the container
-d: run as a daemon
-postgres:latest: the name and the tag of the container in the docker hub
```
