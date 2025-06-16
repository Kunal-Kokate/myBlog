---
date: '2025-06-15T08:59:45-05:00'
draft: false
toc: true
title: 'dbt Fundamentals'
tags: ["DBT", "Data Analysts", "Data Engineers"]
categories: ["DBT", "Course Notes"]
---

## Introduction to dbt
- [dbt Fundamentals Course Link](https://learn.getdbt.com/courses/dbt-fundamentals)

### Traditional Data Teams
Traditional Data Teams typically have two roles:
- #### Data Analysts
    - Tend to work a little bit closer to the business decision makers in finance, marketing, and other departments
    - They typically query the tables that the data engineer has built to serve
    - Analysts skill set usually involves Excel and SQL to query those underlying tables
- #### Data Engineers
    - In charge of building the infrastructure that the data is hosted on, usually databases
    - They also manage the ETL(Extract, Transform, Load) process for making sure the data is where it needs to be and in tables so that the analysts can then query it
    - Skill set for a data engineer includes SQL, Python, Java. and other functional programming languages

Analysts know what to be built so that business decision makers can make those decisions
Data engineers has the skills to build that, put that in production 

### ETL and ELT

#### ETL (Extract --> Transform --> Load)
- Data is taken out of a database, transformed on some third party machine  and then loaded back into the database so that data analysts can query the data

Data warehouse is the coupling of a database and a supercomputer that can run transformations run code on that database.
This is extremelly useful because you can just take raw data, get that into your data warehouse, and then transform it from there. There's no longer this extract load extract load process every time you want to rebuild new database objects.

#### ELT (Extract --> Load --> Transform)
 - Extract data from some source and load it into our data warehouse 
 
 ELT shifts focus to:
 1. Get the data in the warehouse
 2. Transform the data from there

 Cloud-base Data Warehouses Offer:
 1. Scalable compute
 2. Scalable storage
 3. Rduction of transfer time

 ### Analytics Engineer
- Analytics Engineer is focused on taking that raw data and transforming it into transformed data so that the analysts can take it from there and serve whatever needs the business has. 
Really in charge of the T in ELT
- This then frees up the data engineer to focs on the extracting from sources and then loading into the data warehouse or the EL in ELT. 
- THe analyst, they can work more closely with the analytics engineer to deliever these final tables that can then be queried with a BI tool in a much faster way so that they can get what they need when they need

![image](/img/dbtAnalyticsEngineering.png "Table Showing Different Roles")

## How dbt Works



## Project Setup



## Building Models



## Refactoring with `ref()`



## Testing Your Data



## Documentation


## Sources and Seeds


## Jinja and Macros


## Deploying dbt


## Final Project

## Next Steps
