# SpringBoot and Angular project
Sample project using maven frontend plugin in order to have all the code in an unique jar

## Requisites
1. JDK 8
1. [Angular CLI](https://cli.angular.io/)
1. [Node JS](https://nodejs.org/en/)

## Overview

This project has 3 main modules:
1. Demo Spring Boot parent
1. Demo Spring Boot Backend
1. Demo Spring Boot Frontend

## Build Project

Go to parent project and run `mvn clean install`

## Running FE and BE independently 
1. Backend
  1. Access backend project folder and type `mvn spring-boot:run`
1. Frontend
  1. Access frontend project folder and type `ng serve`
  
## Running all together
1. In the parent project folder, type `java -jar demo-springboot-angular-be\target\demo-springboot-angular-be-0.0.1-SNAPSHOT.jar`
2. Application should be accessible now typing `localhost:8080` in the browser


