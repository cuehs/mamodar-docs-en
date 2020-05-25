Run project
===========

1. Start database (if not started already)  
   1.1. Start a shell (*cmd.exe*)  
   1.2. Navigate to your PostgreSQL installation path (i.e. `C:\\[USERPATH]\\bin\\pgsql`)  
   1.3. Start PostgreSQL `pg_ctl.exe start -D "C:\\[USERPATH]\\bin\\pgsql\\data"`  
2. Start backend  
   2.1. In Visual Studio Code: Got to Terminal in the Taskbar at the top  
   2.2. Run task: `gradle:server:bootRun`  
3. Start frontend  
   3.1. In Visual Studio Code: Got to Terminal in the Taskbar at the top  
   3.2. Run task: `npm: start -web`  
4. Open a browser at http://localhost:4200/  
