# 🚖 TAXI SERVICE 🚖
![pic](src/main/resources/images/taxi.jpeg)
## Contents
___
- [Description📕](#Description📕)
- [Features⚙](#Features⚙)
- [Project structure⛓](#Project-structure⛓)
- [Technologies💻](#Technologies💻)
- [How to run project🚀](#How-to-run-project🚀)
___
<a name="Description📕"></a>
## Description📕
This project is simple implementation of real taxi service app
___
<a name="Features⚙"></a>
## Features⚙
- registration like a driver;
- authentication like a driver;
- create/update/remove a driver;
- create/update/remove a car;
- create/update/remove a manufacturer;
- display list of all drivers;
- display list of all cars;
- display list of all manufacturers;
- display all cars for authenticated driver;
___
<a name="Project-structure⛓"></a>
## Project structure⛓
Project is built on a three-tier architecture:
1. Presentation layer (controllers);
2. Application layer (service);
3. Data access layer (DAO)
### Table relation
![relation](src/main/resources/images/relations.png)
___
<a name="Technologies💻"></a>
## Technologies💻
- Apache Tomcat (v. 9.0.50)
- MySql
- JDBC
- Servlet
- JSP, JSTL
- HTML, CSS
- Maven
- Maven Checkstyle Plugin
___
<a name="How-to-run-project🚀"></a>
## How to run project🚀
### Necessary tools
- Intellij IDEA Ultimate
- MySql 
- Apache Tomcat
1. Clone this project
2. In MySql Workbench run query from init_db.sql
3. Add new configuration TomCat Local server
4. Change username and password in ConnectionUtil
5. Add absolute path to .log file in log4j2.xml file
