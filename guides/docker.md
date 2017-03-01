Docker guide
============

Useful docker stuff

 
Commands:
---------

   Delete all containers `docker rm $(docker ps -a -q)`, forced `docker rm -f $(docker ps -a -q)`
   Delete all images `docker rmi $(docker images -q)`, forced `docker rmi -f $(docker images -q)`
   
   Show running container stats in pretty format:
   ```
   docker stats --format "table {{.Name}} \t {{.MemUsage}}"
   ```


