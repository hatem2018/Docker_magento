# Docker_magento
Docker Info
Your database is persistent due to a data volume contained in the docker-compose.yml file. This means that when you tear down the virtual machine and spin it back up at a later date or time, your database will still be intact and ready to go.
If you would like to use Sequel Pro or some other tool to connect to the database, it is accessible at 127.0.0.1:3306. The username is root and the password is root. The name of the database is magento.
The VM includes phpMyAdmin for your convenience. It can be accessed from a web browser at 127.0.0.1:8080.
