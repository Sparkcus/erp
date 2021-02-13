# Enterprise Resource Planning Software

Enterprise Resource Planning Software helps company to manage financial, HR, sales, marketing, manufacturing, 
or supply chain operations. This project provides a demo code to achieve that.

### Features of the ERP Software
Provide interfaces to manage User, Role, Logs, Supplier,  Customer, Commodity, Inventory, Purchase/return,
Commodity loss report, Raw materials purchase, Sales statistics, Commodity sales analysis and statistics on a daily basis. 

### Tech Stack:
- FrontEnd: JavaScript + bootstrap + jQuery + Highcharts + easyUI
- BackEnd: Java + Spring Boot + Spring Data JPA + Apache Shiro
- Database: MySQL

### Deployment Steps:
- Create database and tables using db.sql which is in the path resource/sql/db.sql
- Configure the database connection. The configuration file is /src/main/resources/application.yml. 
Please modify lines 9 to 11. 
- Startup this springboot application. Run src/main/java/com/yufeng/JxcApplication.java
- Open browser, access localhost:80. The username is admin and the passcode is 1.




