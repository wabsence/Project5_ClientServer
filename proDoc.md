# PROJECT DOCUMENTATION

## Step 1: Install Mysql Server in DB_Server

#### Command: sudo apt update -y (update ubuntu packages)
#### Output:

![Update](images/update.png "packages update process")

#### Command: sudo apt install mysl-server -y 
#### Output:

![mysqlServer](images/msqlServer.png "msql server installation")

## Step 1: Install Mysql Client in Client_Server

#### Command: sudo apt update -y (update ubuntu packages)
#### Output:

![Update](images/update2.png "packages update process")

#### Command: sudo apt install mysl-client -y 
#### Output:

![mysqlClient](images/mysqlClient.png "msql server installation")

### Create user, database and grant permission on mysql_server

![User_DB](images/createUSERDB.png "Create user and grant permission")

#### Setting the inbound rules in mysql server security group.

![securityGroup](images/securityGroup.png "Mysql Server security group")


#### Configure MySQL server to allow connections from remote hosts.

![remoteConfig](images/remoteConfig.png "Mysql Server remote host configuration")

## From Mysql Client: connect remotely to mysql server database engine without using ssh

![remoteAccess](images/remoteAccess.png "msql server remote access from mysql client")