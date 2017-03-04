Linux commands guide
====================

Useful commands
---------------

   Show size in Megabytes: `ls -alF --block-size=M <file_path>`
   
   Show volume of hard drive partitions: ` df --block-size=G` 


CSV files manipulation
----------------------

   Change file encoding: `enconv -L ru -x utf-8 <file_path>`
   
   Delete empty lines: `sed -i '/^[ \t\r]*$/d' <file_path>`
   
   Number of rows: `wc -l <file_path>`
   
   
Launching commands in background
--------------------------------

   Launching in background until exit:
   ```bash
   <command> > /dev/null 2>&1 &
   ```
   
   View commands: `jobs`
   
   Kill commands: `kill %n`
   
   Launching in background not terminating on exit:
   ```bash
   nohup <command> > /dev/null 2>&1 &
   ```
   
<!--`sed` usage-->
<!--------------->

