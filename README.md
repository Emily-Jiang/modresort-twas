# ModResorts Demo Application

## About
This version of the applicaiton works on tWAS. This app can be migrated to Java 21 and Jakarta EE 10 and works on MoRE.

## Building and Running
Application can be build with standard Maven lifecycle commands:

```
mvn clean package
```

The Liberty maven plugin is added to the pom.xml to facilitate running of the application in your development environment.

## Dependencies
Application currently has dependencies on a DB2 database and IBM MQ queue manager as described in the server.xml.

