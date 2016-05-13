# Overview of Azure Resource Manager Web App Templates
In this folder, you'll find my Azure Resource Manager Web App templates. You can deploy an Azure Resource Template by clicking on the "Deploy to Azure" banner in the folders.

** Details: **
- The Web App needs to be linked to an existing App Service Plan.
- When a MySQL Database is deployed, the deployment doesn't configure the Connection String for the MySQL Database.

## Episerver-Web-App

Creates the following resources:
- Resource Group
- Storage Account
- Redis Cache
- Web App 
- SQL Server
- SQL Database
- Service Bus

## Episerver-Webshop

Creates the following resources:
- Resource Group
- Storage Account
- Redis Cache
- 2x Web App
- SQL Server
- 2x SQL Database
- Service Bus

## dotNET-Web-App

Creates the following resources:
- Resource Group
- Web App
- SQL Server
- SQL Database

## PHP-MySQL-Web-App

Creates the following resources:
- Resource Group
- Web App
- MySQL Database

## Static-HTML-Web-App

Creates the following resources:
- Resource Group
- Web App