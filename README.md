# dockerfiles-ubuntu-user-adderable
Ubuntu, It support base user creation and password setting.

# Building & Running

Copy the sources to your docker host and build the container, and to run.
```
	docker build --rm -t skbracket1/ubuntu .
	docker run -it --name u1 -e USER=skbracket1 -e PASSWD=skbracket1 skbracket1/ubuntu
```
Get the port that the container is listening on:

```
# docker ps
CONTAINER ID        IMAGE               COMMAND             CREATED             STATUS              PORTS               NAMES
ad2ad96e4b2f        skbracket1/ubuntu      "/bin/bash"         7 seconds ago       Up 6 seconds                            u1
```

To test, ("skbracket1" is username. )
```
	su - skbracket1
```
To Rollback
```
    docker rm u1 -f
    docker rmi skbracket1/ubuntu
```
#   d o c k e r _ u b u n t u  
 #   d o c k e r _ u b u n t u  
 #   d o c k e r _ u b u n t u  
 #   d o c k e r _ u b u n t u  
 #   d o c k e r _ u b u n t u  
 #   d o c k e r _ u b u n t u  
 #   d o c k e r _ u b u n t u  
 #   d o c k e r _ u b u n t u  
 #   d o c k e r _ u b u n t u  
 