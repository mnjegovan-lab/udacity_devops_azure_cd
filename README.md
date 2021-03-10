# Overview

![Build Status](https://dev.azure.com/njegovan/Flask%20Pipelines/_apis/build/status/mnjegovan-lab.udacity_devops_azure_cd?branchName=master&stageName=Deploy%20Web%20App)


<TODO: complete this with an overview of your project>

## Project Plan
<TODO: Project Plan

* A link to a Trello board for the project
* A link to a spreadsheet that includes the original and final project plan>

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service

![Azure App Service](./screenshot/azure_app_service.jpg)

* Project cloned into Azure Cloud Shell

![Azure Cloud Shell](./screenshot/cd_git_clone.jpg)

* Passing tests that are displayed after running the `make all` command from the `Makefile`

![MakeFile test](./screenshot/make_all_succesfull.jpg)

* Output of a test run

![Output](./screenshot/output_of_ a_test_run.jpg.jpg)

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

![Azure App Service from Azure Pipelines automatic deployment](./screenshot/azure_deploy_web_app_pipeline.jpg)

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:


![App prediction](./screenshot/make_prediction_azure_app.jpg)

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

https://mnjegovan-flaskpipelines.scm.azurewebsites.net/api/logs/docker

![streamed_log](./screenshot/streamed_log.jpg)

```json
[{
"machineName":"pl0sdlwk00001I_default",
"lastUpdated":"2021-03-10T11:51:47.8195533Z",
"size":23382,
"href":"https://mnjegovan-flaskpipelines.scm.azurewebsites.net/api/vfs/LogFiles/2021_03_10_pl0sdlwk00001I_default_docker.log",
"path":"/home/LogFiles/2021_03_10_pl0sdlwk00001I_default_docker.log"
},
{
"machineName":"pl0sdlwk00001I",
"lastUpdated":"2021-03-10T11:51:06.9256643Z",
"size":1582,
"href":"https://mnjegovan-flaskpipelines.scm.azurewebsites.net/api/vfs/LogFiles/2021_03_10_pl0sdlwk00001I_docker.log",
"path":"/home/LogFiles/2021_03_10_pl0sdlwk00001I_docker.log"
}]
```

View the log file in Azure App Service - Log Stream :
![azure_log_stream](./screenshot/azure_log_stream.jpg)



## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


