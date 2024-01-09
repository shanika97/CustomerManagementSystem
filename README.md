# CustomerManagementSystem
CUstomer management System (Struts2 jsp curd jdbc project)
frontend for jsp
backend for struts2
server tomcat 8.5
database mysql
Eclipse idea 4.7 (Oxygen)

#using mysql for database
CREATE DATABASE 'users';
USE users;

create table customer (
 id  int(3) NOT NULL AUTO_INCREMENT,
 name varchar(120) NOT NULL,
 email varchar(220) NOT NULL,
 phone varchar(10) NOT NULL,
 username vatchar(10) NOT NULL,
 password varchar(8) NOT NULL,
 PRIMARY KEY (id)
);

#Tomcat server 8.5
https://tomcat.apache.org/download-80.cgi
mysqlConnect 5.1.49(bin).jar
 Struts2 jar files include in zip
