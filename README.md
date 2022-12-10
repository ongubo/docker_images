# dockerimages

A list of docker images i commonly use for my machine

## Getting started

install docker and add docker in list of users to avoid using sudo

```
sudo groupadd docker

sudo usermod -aG docker $USER

```
 Then restart machine or quick fix
 
 
```
newgrp docker
```
 
## Remember
To cjheck network for the running service

```
docker inspect mysql_container --format='{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}'
```

## Integrate with your tools

- [ ] [Set up project integrations](https://gitlab.com/kadabus/dockerimages/-/settings/integrations)


