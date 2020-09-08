# Overview
Building a CI/CD is the second project in Udacity Azure DevOps ND. This presentation highlights the process of building a CI/CD pipelines using Github and Azure technologies. 


![CI](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/workflows/CI/badge.svg)

## Project Plan
Project Plan

* A link to a Trello board for the project
https://trello.com/b/4J77G7tb/udacity-azure-cloud-devops-nd?raw=true
* A link to a spreadsheet that includes the original and final project plan>
https://docs.google.com/spreadsheets/d/1AZMtpwwCM4olytDRDnzc3QWygjhnXiKNCb-HX5baIdA/edit?usp=sharing

## Instructions


* Architectural Diagram (Shows how key parts of the system work)>
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Building%20CICD%20in%20Azure%20Architectural%20Diagram(1).png?raw=true)


Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

Steps:
1. Login Azure cloud
2. Click on Cloud Shell in top navbar to launch Azure cloud shell
3. Clone the project repository - `git@github.com:Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines.git`
4. Change directory to the cloned project
5. Deploy to Azure App Service using shell script command.sh in the root directory
   `./commands.sh`
6. Verify the application is deployed by browsing the url 
7. Execute the script make_predict_azure_app.sh to make a prediction. The out should look like the below:

   `./make_predict_azure_app.sh`
   
```bash
Port: 443
{"prediction":[20.35373177134412]}
```


* Project running on Azure App Service
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Screen%20Shot%202020-09-07%20at%203.56.12%20PM.png?raw=true)

* Project cloned into Azure Cloud Shell

![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Screen%20Shot%202020-09-04%20at%2010.11.05%20AM.png?raw=true)


* Passing tests that are displayed after running the `make all` command from the `Makefile`

![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Screen%20Shot%202020-09-04%20at%2010.25.10%20AM.png?raw=true)



* Output of a test run
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Screen%20Shot%202020-09-04%20at%2010.42.00%20AM.png?raw=true)

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Screen%20Shot%202020-09-07%20at%203.51.50%20PM.png?raw=true)


* Azure App Service
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Screen%20Shot%202020-09-08%20at%209.15.00%20AM.png?raw=true)

* Running Azure App Service from Azure Pipelines automatic deployment
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Screen%20Shot%202020-09-07%20at%203.54.11%20PM.png?raw=true)

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Screen%20Shot%202020-09-07%20at%203.56.12%20PM.png?raw=true)


* Output of streamed log files from deployed application
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/Screen%20Shot%202020-09-07%20at%204.03.20%20PM.png?raw=true)
> 


## A load test with locust
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/locust1.png?raw=true)
![alt text](https://github.com/Julyseven2002/Udacity-Azure-DevOps-Building-a-CICD-Pipelines/blob/master/locust2.png?raw=true)

## Enhancements


1. Add integration test and configure it to run in CI. 
2. Automate the CI/CD using Infrastruture as Code

## Demo 

Add link Screencast on YouTube
https://youtu.be/Jf3IZG-pKsU

