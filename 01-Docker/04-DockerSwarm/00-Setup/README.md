```
    1  ls
    2  cd 01-Docker/
    3  ls
    4  mkdir 04-DockerSwarm/00-Setup -p 
    5  ip addr 
    6  docker ps
    7  docker kill $(docker ps -aq) 
    8  docker rm $(docker ps -aq) 
    9  docker ps -a 
   10  ip addr 
   11  docker swarm init --advertise-addr <<master-private-ip-address>>
   12  docker info 
   13  netstat -tulnp 
   14  docker ps 
   15  docker ps -a
   16  docker node ls
``` 
