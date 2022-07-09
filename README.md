# JavaSwingStudentMgmtProject

## Instructions on how to setup the environment

### IDE : IntelliJ IDEA
This editor is recommended for use because the project was developed using the same. For execution without any kind of  platform specific errors kindly use the same.

### Adding MySQL Connector (JDBC), and rs2xml.jar
For adding the MySQL connector(JDBC) along with the rs2xml.jar to the project structure, kindly follow the following youtube video (Link: https://www.youtube.com/watch?v=e3AKnrTxFFo) Time Stamp : 12:00 to 13:15.
  
  For designing the user interface using the Palette in swing, the same video can be referred as well.
  
### Adding the username and password (MySQL) in the code
For adding the MySQL username and password, create a file config.properties in the src folder.

 File Location: /src/

Syntax:

`prop1 = 'username'`

`prop2 = 'password'`

Replace 'username' with respective username and 'password' with respective password of MySQL.

NOTE do not include any type of quotes ' or ".

Eg:

`prop1 = user`

`prop2 = password`

While running the application the username and password will be fetched from this file automatically and placed in the string variables uname and pswd in the code.

If you encounter the SQLException, then just copy the config.properties file from src/config.properties and paste it into the directory /out/production/StudentMgmtSys

So we must have two config.properties files in two locations as listed below:

1. /src/config.properties

2. /out/production/StudentMgmtSys/config.properties
