Docker guide
============

Useful docker stuff

 
Commands:
---------

   Delete all containers: `docker rm $(docker ps -a -q)`
   
   Delete all images: `docker rmi $(docker images -q)`
   
   Show running container stats in pretty format:
   ```bash
   docker stats --format "table {{.Name}} \t {{.MemUsage}}"
   ```
   
   ```js
   var fun = function lang(l) {
    dateformat.i18n = require('./lang/' + l)
    return true;
   }
   ```


