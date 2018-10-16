# Psql Console Commands

## Basics
Tool | Command |
--- | --- |
Start Console       |`psql postgres`
List Users          |`\du`
List Databases      |`\list`
Connect to Database |`\connect <name>`
Exit Console        |`\q`


## Databases 
Tool | Command |
--- | --- |
List Tables        |`\dt`
Create Database    |`CREATE DATABASE <name>;`

## Users
Tool | Command |
--- | --- |
Create User        |`CREATE ROLE <name> WITH LOGIN PASSWORD '<password>';`
Grant Privilege    |`GRANT ALL PRIVILEGES ON DATABASE <database> TO <user>;`

## Schemas
Tool | Command |
--- | --- |
List Schemas       |`\dn`
List Schema Tables |`\dt <schema>.*`

