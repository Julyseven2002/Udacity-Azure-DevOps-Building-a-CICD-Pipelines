# Overview
Building a CI/CD is the second project in Udacity Azure DevOps ND. This presentation highlights the process of building a CI/CD pipelines using Github and Azure technologies. 


![CI](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/workflows/CI/badge.svg)

## Project Plan
<TODO: Project Plan

* A link to a Trello board for the project
https://trello.com/b/4J77G7tb/udacity-azure-cloud-devops-nd?raw=true
* A link to a spreadsheet that includes the original and final project plan>
https://docs.google.com/spreadsheets/d/1AZMtpwwCM4olytDRDnzc3QWygjhnXiKNCb-HX5baIdA/edit?usp=sharing

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Building%20CICD%20in%20Azure%20Architectural%20Diagram(1).png?raw=true)


<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

Steps:
1. Login Azure cloud
2. Click on Cloud Shell in top navbar to launch Azure cloud shell
3. Clone the project repository
4. Change directory to the cloned project
5. Deploy to Azure App Service using shell script command.sh in the root directory
   `./commands.sh`
6. Verify the application is deployed by browsing the url 
7. Execute the script make_predict_azure_app.sh
   `./make_predict_azure_app.sh`
   
```bash
Port: 443
{"prediction":[20.35373177134412]}
```


* Project running on Azure App Service
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Building%20CICD%20in%20Azure%20Architectural%20Diagram(1).png?raw=true)

* Project cloned into Azure Cloud Shell

* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

Add link Screencast on YouTube
https://youtu.be/Jf3IZG-pKsU

