Backend
* .netcore
* Java spring boot
* go 
* nodejs
Frontend
* React
* Vue
* Angular
Base de datos
* Sql Server
* Oracle
* Mysql
## Instalar neo4j
* wget --no-check-certificate -O - https://debian.neo4j.org/neotechnology.gpg.key | sudo apt-key add -
* sudo echo 'deb https://debian.neo4j.org/repo stable/' | sudo tee -a /etc/apt/sources.list.d/neo4j.list
* sudo apt update
* sudo apt install neo4j


* sudo vim /etc/neo4j/neo4j.conf
* dbms.connectors.default_listen_address=0.0.0.0
* dbms.security.auth_enabled=false

* username: neo4j - password: neo4j
