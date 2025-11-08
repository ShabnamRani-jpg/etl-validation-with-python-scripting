# ETL-Validation-with-python-scripting
Cross DB ETL Validation (Oracle to postgresql) with python scripting

## Table of Contents

* [Overview](#overview)
* [ETL Validation using Python scripting](#etl-validation-using-python-scripting)
* [Design and Development](#design-and-development)
* [Data Validation](#data-validation)
* [Authors](#authors)
* [About the Maintainer](#about-the-maintainer)


## Overview

Design and Develop ETL pipeline from Oracle to Postgresql using informatica Powercenter.
Perform ETL validation using Python scripting.

## ETL Validation using Python scripting


* Connect to Source: oracle DB from Config file
* Read Source queries and load to DataFrame
* Connect to Target: pgAdmin from config file
* Read Target Queries and load to DataFrame
* Validate data with the help of Pandas module in python
* Check for count, duplicates, null, truncation and transformation in source and target
* Write test results into a separate file

![image](https://github.com/varma-prasad/ETL-Validation-with-python-scripting/assets/108605375/ab05e467-3c55-496b-8131-e998346a9dbe)

## Design and Development

* Import source and target details to the Designer
* Design Mapping from source to target with necessary transformation
* This is Cross DB ETL. Source is Oracle and Target is Pgadmin
* Lookup Transformation is used to fetch department name
* Filter transformation to limit the entry of data into target table
* Expression transformation used to replace null values for designation
* Sorter transformation is used to get distinct employee ids and to sort employees in Ascending order

![image](https://github.com/varma-prasad/ETL-Validation-with-python-scripting/assets/108605375/a57a5f90-4b4d-4820-be7b-d250e1bee1ad)
![image](https://github.com/varma-prasad/ETL-Validation-with-python-scripting/assets/108605375/4d1a861d-bc8b-46db-94ea-7c464f214e69)

## Data Validation

* Check Run properties and session logs for the detailed report
* Check Count in Source and Target tables
* Check all the transformation logic are fulfilled such as (duplicates not loaded, Null values replaced)
* Check any data is truncated
* Using python scripts automate the testing of data validation and get results into a text file.

![image](https://github.com/varma-prasad/ETL-Validation-with-python-scripting/assets/108605375/86e4b659-5850-4de0-a0d9-b5c88cc58e54)

----

## Tools used
![](https://img.shields.io/badge/Informatica_Powercenter-v10.2.0-purple)
![](https://img.shields.io/badge/Oracle_Database_21c-v21.1.0-green)
![](https://img.shields.io/badge/PostgreSQL-v16.0.0.1-blue)
![](https://img.shields.io/badge/python-v3.12.1-orange)

## Authors

- [Shabnam Rani] (Current Maintainer)
- [Varma Prasad S](https://github.com/varma-prasad) (Original Contributor)

## Skills
SQL, ETL, Python, Power BI...

## Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/varma-prasad-s/)

## About the Maintainer

This project is actively maintained by Shabnam Rani, a Business Analyst with 2+ years of experience in data analysis and process optimization. Shabnam specializes in leveraging Python scripting and SQL for robust ETL validation and data insights.

Connect:
- LinkedIn: [Shabnam Rani](https://www.linkedin.com/in/shabnam-rani-61191b15a)
- Email: shabnamr214@gmail.com
