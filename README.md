# Setting-mysql-server in CENTOS
Setting mysql server

# 1. Setting mysql server
    update version:  yum update && yum upgrade
    setting wget: yum install wget
    wget http://repo.mysql.com/mysql-community-release-el7-8.noarch.rpm 
        or wget http://repo.mysql.com/mysql-community-release-el7-5.noarch.rpm
    mysql: sudo yum install mysql-server
    start: sudo systemctl start mysqld
    
    
