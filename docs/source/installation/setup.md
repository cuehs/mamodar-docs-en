Set Up
======

Create a PostgreSQL database
-----------------------------

1. Start a shell (*cmd.exe*)
2. Navigate to your PostgreSQL installation path `$postgres` (i.e. `C:\\[USERPATH]\\bin\\pgsql`)
3. Go into the `\bin` subdirectory (`cd bin`)
4. Create a data directory (`mkdir data`)
5. Start PostgreSQL `pg_ctl.exe start -D "C:\\[USERPATH]\\bin\\pgsql\\data"`
6. Create the *mamodar* database `createdb.exe mamodar`

Set-Up
------

1. Start Visual Studio Code
2. Install two *Extensions* (fifth icon on the left bar):  
   2.1 *Gradle Tasks* (richardwillis.vscode-gradle)  
   2.1 *npm* (eg2.vscode-npm-script)  
3. Update `server\\application.properties`   
   3.1. Fill in `spring.datasource.username` and `spring.datasource.password` using the PostgreSQL data  
   3.2. Update `rdmo.token` and `rdmo.url` to point to a previously setup RDMO server
4. In *Source Control* (third icon on the left bar)  
   4.1. Clone repository: https://github.com/cuehs/mamodar.git  
   4.2. Select a  local folder to clone code to (no server!)  
   4.3. Open folder in Visual Studio Code  
5. Go to *Terminal*, Run task: `npm: build -web`  
