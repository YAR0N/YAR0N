Linux commands guide
====================

CSV files manipulation
----------------------

   Change file encoding: `enconv -L ru -x utf-8 <file_path>`
   
   Delete empty lines: `sed -i '/^[ \t\r]*$/d' <file_path>`
   
   Number of rows: `wc -l`
   
   
Launching commands in background
--------------------------------

   Launching in background until exit:
   ```
   <comand> > /dev/null 2>&1 &
   ```
   
   View commands: `jobs`
   
   Kill commands: `kill %n`
   
   Launching in background not terminating on exit:
   ```
   nohup <comand> > /dev/null 2>&1 &
   ```