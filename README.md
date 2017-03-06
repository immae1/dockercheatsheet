# dockercheatsheet
# Useful commands 
## Show Names in Stats:
`docker stats $(docker ps --format={{.Names}}) `
## load .profile without ssh with docker exec command for 
`docker exec -it containername /bin/bash -c ". /home/username/.profile; /bin/bash ./scriptToStart.sh" ` 
