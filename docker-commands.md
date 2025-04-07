# Docker basic Commands

| Command                               | Description                               |
|---------------------------            |------------                               |
|docker images                          | It shows all images                       |
|docker ps                              | It gives all running containers           |
|docker ps -a                           | It gives all running/stopped containers   |
|docker run #image_name#                | It will run container                     |
|docker run -it #image_name#            | It will run container in attached mode    |
|docker stop #container_id#             | It will stop container                    |
|docker start #container_id#            | It will start container                   |
|docker run -p #external_port# : # internal_port# #image_name#  | It will run container with port. So we can access on local. Internal port means docker port
|docker logs #container_id#             | It will gives logs
|docker exec -it #container_id# #command# | Using exec will excute commands inside docker container from local terminal

