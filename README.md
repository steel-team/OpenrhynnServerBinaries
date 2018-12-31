# OpenrhynnServerBinaries
Contains ready to use ORServer

Requirements:
Java 1.8 required to run server

How to launch server:
1) download this repository and unpack to any directory
2) download OpenrhynnServerContent repository and unpack to same directory
3) edit configs/database.json change openrhynn to database name, set login and password
4) download sql file from OpenrhynnJavaServer repository (database/openrhynn.sql) and import to mysql database
5) run server via run.bat on windows and run.sh on linux


How to launch client:
1) download OpenRhynn client sources(it's important to use exactly OR client, not rhynn) from http://openrhynn.net/sources/publ/client/client.zip
2) change FantasyWorldsGame.java, set DEFAULT_PACKETPERLOOP to 5000, set defaultHost to your ip(or 127.0.0.1 if you test locally)
3) compile client (use guide from macrolutions ltd https://github.com/marlowe-fw/Rhynn/wiki/Building-the-Client)
4) run client :)
