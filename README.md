# BirdStrikeData

## Overview
This document provides the code for a Practicum project in CS5200, Spring 2023. The project involves setting up a local MySQL database, creating tables for wildlife strike incidents, airports, airlines, and conditions. It also includes loading data from a CSV file into the tables, running SQL queries, and implementing a stored procedure for adding new incidents.

## Instructions

### Connect to Database
Before running any code, make sure to set up a local instance of MySQL. Modify the database connection parameters in the code to match your configuration.

```R
# Modify these parameters accordingly
db_user <- 'root'
db_password <- 'your_password'
db_name <- 'your_database'
db_host <- '127.0.0.1'
db_port <- 3306
