# Deploys three-node Elasticsearch cluster running in Docker containers on Virtual machine in Availability set

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3a%2f%2fraw.githubusercontent.com%2ftlavrent%2ftemplate%2fmaster%2fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


This template allows you to deploy a three-node Elasticsearch cluster running in Docker containers on Virtual machine. Virtual machine is deployed in Availability set on Virtual Network with one Subnet and is assigned public IP address. Location is inherited from Resource Group.

Below are the parameters that the template expects

| Name   | Description    |
|:--- |:---|
| storage account | storage account in the same location as resource group |
| admin user name | admin user name for VM's |
| admin password| admin password for VM's |
| VM public ip address| VM public IP address |
| VM size| default value is 'Standard_D1' |