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
* http://<IP address/DNS for linux machine>:7474/browser/
* username: neo4j - password: neo4j

### neo4j configuration (/etc/neo4j/neo4j.conf)
* dbms.connector.bolt.enabled=true
* dbms.connector.bolt.listen_address=0.0.0.0:7687
* dbms.connector.http.enabled=true
* dbms.connector.http.listen_address=0.0.0.0:7474
* dbms.connectors.default_listen_address=0.0.0.0
* dbms.security.auth_enabled=false
#### increase the heap size 
* dbms.memory.heap.initial_size=4g
* dbms.memory.heap.max_size=4g
## HADOOP
* https://hadoop.apache.org/docs/r2.8.2/hadoop-project-dist/hadoop-hdfs/HDFSHighAvailabilityWithQJM.html
