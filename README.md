# flask-sklearn
azure devops final project
Overview
This is the demo project for final ci-cd azure pipeline. 

Project Plan

A link to a Trello board for the project: 
https://trello.com/b/aQyWozwu/calendar-project

A link to a spreadsheet that includes the original and final project plan: https://docs.google.com/spreadsheets/d/1wT3J8EIGwIcjbVPyDPGbF5SCC7qb6S12Np_7bWDoNzc/edit#gid=1348135932

Instructions

Project running on Azure App Service
https://flask-sklearn.azurewebsites.net/

Project cloned into Azure Cloud Shell
https://github.com/kishanp8/flask-sklearn

Passing tests that are displayed after running the make all command from the Makefile
![alt text](https://github.com/kishanp8/azure-ci-cd-project/blob/main/passes_test.PNG)

Output of a test run

Successful deploy of the project in Azure Pipelines. Note the official documentation should be referred to and double checked as you setup CI/CD.
![alt text] (https://github.com/kishanp8/flask-sklearn/blob/main/deployment_success.PNG)

Running Azure App Service from Azure Pipelines automatic deployment

Successful prediction from deployed flask app in Azure Cloud Shell. Use this file as a template for the deployed prediction. The output should look similar to this:

udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
Output of streamed log files from deployed application
Enhancements
<TODO: A short description of how to improve the project in the future>

Demo
<TODO: Add link Screencast on YouTube>
