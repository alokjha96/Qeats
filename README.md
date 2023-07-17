# Qeats - [A Java with SpringBoot based food ordering app]
<p align="center"> 
<img width="200" height="200" src="https://github.com/alokjha96/Qeats/blob/main/qeats%20logo.png">

## Overview

*QEats is a popular food ordering app that allows users to browse and order their favorite dishes from nearby restaurants.*
 During the course of this project
 1) I had build different parts of the QEats backend which is a Spring Boot application.
 2) Several REST API endpoints were implemented to query restaurant information and place food orders.
 3) To give a sense of real-world problems, production issues were investigated using Scientific Debugging methods.
 4)  Along with this, I improved the app performance under large load scenarios as well as included an advanced search feature in the app.
 
---
## Perform search operations using custom attributes

### Scope of Work

- Used MongoDB queries to enable users to search for restaurants using attributes like name, cuisine, dish, and price.
- Used multithreading to increase the number of concurrent searches that can be performed.

### Skills used

MongoDB querying, Multithreading

<img src = "https://github.com/alokjha96/Qeats/blob/main/qeats2.PNG">
<img src="https://github.com/alokjha96/Qeats/blob/main/qeats3.PNG">
<img src="https://github.com/alokjha96/Qeats/blob/main/qeats4.PNG">


## Retrieve restaurant data for a given user location

### Scope of Work

- Implemented GET /API/v1/restaurants and the corresponding request handler and response methods.
- Used Mockito to enable the development of the relevant MVCS layers independently.
- Retrieved a list of restaurants from MongoDB based on a user location.


### Skills used

Spring Boot, Spring Data, REST API, Jackson, Mockito, JUnit, MongoDB

<img src = "https://github.com/alokjha96/Qeats/blob/main/qeats5.PNG">



## Replicate performance issues and solve them using caching strategies

###  Scope of Work

- Employed JMeter or load testing to expose performance issues.
- Identified DB queries contributing to degradation in performance.
- Used a Redis cache to alleviate read performance.


### Skills used

Redis, JMeter


## Resolve production issues using Scientific Debugging

###  Scope of Work

- Debug QEats app crashes from backend leveraging log messages and structured debugging techniques.
- Use IDE features (breakpoints) and assert statements to identify the root cause.


### Skills used


Scientific Debugging




