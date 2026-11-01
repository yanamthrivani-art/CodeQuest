CODEQUEST PROJECT
Requirements: JDK 17+, Tomcat 10.1, MySQL, MySQL Connector/J.
1. Run database.sql in MySQL.
2. Open src/main/java/codequest/DB.java and replace YOUR_MYSQL_PASSWORD with your MySQL root password.
3. Add MySQL Connector/J to Java Build Path and keep the JAR in src/main/webapp/WEB-INF/lib.
4. In Eclipse, copy src/main/java contents into your Java source folder and src/main/webapp contents into your web folder. Ensure the project/context root is CodeQuest.
5. Restart Tomcat and open http://localhost:8080/CodeQuest/
Admin username: admin
Admin password: Admin@12345
This is an educational demo; admin password handling is simplified and should not be used in production.
