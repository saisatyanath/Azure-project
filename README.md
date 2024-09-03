# Azure-project


![image](https://github.com/user-attachments/assets/9465cae9-84d4-4ec2-8d1f-4351db116085)


For creating resources in azure, we need to create resource group. So, that all the resouces are tagged to a group.

> storage types in azure
- Blob storage
- file storage
- Queue storage
- Table storage

Related to data:

AWS EMR - Elastic Map Reduce, used for handling higher amount of data

Data lake storage for azure (for storing big data), for storing big data we have

- HDI CLUSTER
- hadoop
- HDFS
- Zookeeper
- worker nodes
- node manager
- resource manager

steps:

login to Azure portal

install the Azure CLI

install Terraform

az login

az account set--subscription="ID "

az ad sp create-for-rbac --role = "contributor" --scopes= "/subscriptions/ID"

sp-> service principle

step5:

az login -- serviveprinciple -u CLIENT_ID -p CLIENT_SECRET --tenant TENANT_ID

clone the code

Add azure Terraform plugin in vs code 






  
