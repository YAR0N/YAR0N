---
title: Postgres
layout: default
---

Postgres guide
==============

Administrative commands
-----------------------

   View current queries:
   ```sql
   SELECT query_start, pid, query FROM pg_stat_activity;
   ```
   
   Terminate query:
   ```sql
   SELECT pg_terminate_backend(<pid>);
   ```