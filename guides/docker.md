Docker guide
============

Useful docker stuff

 
Commands:
---------

   Delete all containers: `docker rm $(docker ps -a -q)`
   
   Delete all images: `docker rmi $(docker images -q)`
   
   Show running container stats in pretty format:
   {% raw  %} 
   ```bash
   docker stats --format "table {{.Name}} \t {{.MemUsage}}"
   ```
   {% endraw  %}
   
Compose:
--------

   Changing running service:
   ```bash
   docker-compose up -d -no-deps <service-name>
   ```
