# Restful booker Api Data Driven Testing Project
Data-driven testing on Restful-booker Api which is a CRUD Web API that comes with authentication features. Utilizing Postman for testing Api and Newman, a Command-line collection runner for Postman, for generating reports.

# Data-Driven Testing
Data-driven testing is a powerful technique to test APIs with varying input data. It is a Test design and execution strategy where the test scripts read test data from data sources such as Excel, JSON files, CSV files, etc. rather than using hardcoded values.

# Advantages of Data-Driven Testing

It will provide the possibility to create Test Scripts at the early stage of development.
Redundancy and duplication of Test Scripts are reduced.
We can generate Test scripts with less amount of code.
All information like inputs, outputs, and the expected result is stored in the form of excel, CSV or JSON files.
Provides flexibility in Test Scripts maintenance.

# Testing Tools used:
Postman
Newman

# Prerequisite:
Node Js
Newman
Html Report Library

# Newman Installation Process:
Install Command:
npm install -g newman

Run Command:
newman run “Path/CollectionName.json” -e Path/EnvironmentName.json
newman run “Collection Link” -e “Path”/EnvironmentName.json

# Report Configure
Install Command:
npm install -g newman-reporter-html
npm install -g newman-reporter-htmlextra

Run Command:
newman run CollectionName.json -e EnvironmentName.json -r cli,html
newman run CollectionName.json -e EnvironmentName.json -r cli,htmlextra

# API Documentation:
https://restful-booker.herokuapp.com/apidoc/index.html

# Steps to perform Data Driven Testing in Postman using Newman CLI.
Create a collection and create the API requests inside the collection.
Add your tests to the API request.

# Data Driven Tests Using CSV file
Create a CSV file.
A screenshot of the CSV file is given below:

![image](https://github.com/nowmezaman/Restful-Booker-API-DDT/assets/17945810/f9337419-2d08-4d24-bcce-93b4b3dad07a)


# Newman CLI
Newman CLI is a powerful tool that can be used to automate API testing and perform data-driven testing. With Newman CLI, you can easily perform data-driven testing and catch bugs and issues early in the development cycle.

![booking ddt1](https://github.com/nowmezaman/Restful-Booker-API-DDT/assets/17945810/595b327b-f7e7-4eae-95a2-bd79842b91ce)


# Newman Summary Report

![image](https://github.com/nowmezaman/Restful-Booker-API-DDT/assets/17945810/fdc5648c-391e-432c-a06f-563a82009a6d)


