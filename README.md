# Acquity Data Warehouse

This repository contains the code for the Acquity Data Warehouse.

## Sentry

We use Sentry to track errors in the data warehouse. You can access the Sentry dashboard [here](https://berry-dev.sentry.io/issues/).
 

 ## api

Api files are navagating data from the data warehouse to the frontend application.
These structure will help you manage and extend your aplication more easily and create more endpoints and functionality.
these routes are used to sync data from the data warehouse to the frontend application.

 ## db

Database files are used to connect to the data warehouse.
Create tables for convoso and retreaver data.

 ## migrations

Migration files are used to create tables and columns in the data warehouse.
The  files are used to create performance summaries and metrics.

 ## services

Service files are used to perform data processing and analysis.
service file collects data from the convoso and retreaver APIs and stores it in the data warehouse.

 ## utils

Utility files are used to perform common tasks. 
Login authentication and authorization is handled here.
sentry is used to track errors in the data warehouse.
Sentry also allows you to monitor the performance of your application by tracking transactions and performance metrics

## taskmanager 

Taskmanager is used to manage the tasks in the data warehouse.
Taskmanager is used to create tasks,  cancel tasks, wait for tasks to complete, and get the status of a task.

## intial review insights 

This is the intial review of the data warehouse.   

Creatation orm models using SQLAlchemy for the tables in the data warehouse.
majorly check the taskmanager and the services files.
Data Synchronization with the data warehouse.
Majorly focus with data sync, prformance metrics, and statistical analysis.