# azure-devops-pipeline-storage-fileshare-copy
This project copies files from Azure git repo to Azure storage fileshare directory using azure devops pipeline </br>

#Pre-requisites:
Create service connection for the resource group you are using in Azure </br>
Pass values to the variables in azure-pipelines ('guru-sv-test'-> Service Connection) </br>
Pass values to "storage-account-name" and "file-share-name" in deploy-params.json </br>

#Conclusion
This project copies files inside "Scripts" folder from azure git repo to Azure storage fileshare directory