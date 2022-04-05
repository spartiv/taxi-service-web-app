# taxi-service-web-app
Taxi-Service
Project description:

Simple web taxi service that uses 3 tier architecture

    DAO - Data access layer
    Service - Application logic layer
    Controllers - Presentation layer

Features:

     creat/update/remove a driver;
     creat/update/remove a manufacturer;
     creat/update/remove a car;
     registration;
     authentication;
    
    display list of all drivers;
    display list of all manufacturers;
    display list of all cars;
    display list of all cars by current driver;
    add driver to car.


Technologies:

    Java 11
    Git
    Apache Maven
    Apache Tomcat
    Apache Log4j 2
    MySQL
    JDBC
    Javax Servlet
    JSP
    JSTL
    HTML/CSS
    Checkstyle plugin

How to run a project:

    Download and install MySQL;
    Download and install Apache TomCat(IMPORTANT! You must use version: 9.0.x);
    Clone this repository;
    Configure Apache Tomcat in your IDEA;
    Copy and run SQL script /src/main/resources/init_db.sql to create a schema and tables required for this project;
    Configure /src/main/java/taxi/util/ConnectionUtil.java by replacement of all plugs such as: URL, USERNAME, PASSWORD, JDBC_DRIVER;
    Configure /src/main/resources/log4j2.xml replace "ABSOLUTE_PATH" with the path to your log file.
    Run project.
