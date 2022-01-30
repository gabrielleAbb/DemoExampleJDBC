# DemoExampleJDBC
 connecting java Project to WampServer 
 Adding data to database 
 using Netbeans IDE 12.6
 
 
 1. you need to download :
-Apache NetBeans IDE 12.6
-  mysql-connector-java-5.1.36-bin.jar
  https://dev.mysql.com/downloads/file/?id=510039

3.Driver Class Used for MySQL:
com.mysql.jdbc.Driver

4. 

4.database:
jdbc:mysql://localhost:3306/demo_db?

5. Query:
query="INSERT INTO user_tb (name, username, password ) VALUES ('"+txtname+"','"+txtuser+"','"+txtpass+"')";
with DemoExampleJDBC you can add a name, username and password to user_tb table then save and it will appear in the table on this link 
 http://localhost/phpmyadmin/sql.php?db=demo_db&table=user_tb&pos=0


