# farithdelgado
db-backup-nfs:/originadores/DATABASE /DATABASE nfs rw,hard,noatime,nodiratime,_netdev,nofail 0 0


###### Scrip
docker exec -i <contenedor> mysql -u root -p -e "ALTER USER 'us.backup'@'localhost' IDENTIFIED BY 'Privacy2024*+'; FLUSH PRIVILEGES;"
