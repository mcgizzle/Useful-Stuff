# Useful console commands

## Basics
Tool | Command |
--- | --- |
Start Console       |`psql postgres`
List Users          |`\du`
List Databases      |`\list`
Connect to Database |`\connect <name>`


## Databases and Users
Tool | Command |
--- | --- |
Create User      |`CREATE ROLE <name> WITH LOGIN PASSWORD '<password>';`
Create Database  |`CREATE DATABASE <name>;`
Grant Privilege  |`GRANT ALL PRIVILEGES ON DATABASE <database> TO <user>;`
Show Tables      |`\dt`
