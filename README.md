---
page_type: sample
languages:
- python
products:
- azure
description: "A collection of labs demonstrating how to build Python applications with Azure and Visual Studio Code."
urlFragment: azure-python-labs
---

# Azure Python Labs

A collection of labs demonstrating how to build Python applications with Azure and Visual Studio Code.

Join the Microsoft Python Discord (http://aka.ms/python-discord ) and the **#python-virtual-labs** channel to ask questions, get help with labs, and/or further instructions (also see: <https://aka.ms/python-virtual-labs> for our PyCon 2020 online experience).


## Sentiment Analysis with Python Azure Functions

In this lab, you will build a serverless HTTP API with Azure Functions that takes a sentence as an input and returns the sentiment of the sentence.

- Build a serverless HTTP API with Azure Functions
- Run and debug the API locally on your machine
- Deploy the API to Azure Functions

[Go to lab](4-azure-functions-python-vscode/README.md) | Duration: 7 minutes


## Hello World in Visual Studio Codespaces

Create and work with an environment in Visual Studio Codespaces, all on the browser.

- How to get started with a GitHub repo
- How to create and run a Hello World in Python
- How to run a Flask app

[Go to lab](9-vscodespaces/README.md)

## Document recognition with Python Azure Form Recognizer

In this lab, you will learn how to quickly store information you collect from your documents and receipts and prepare them for further analysis. You will learn to:

- Deploy new resources in Azure
- Write your own code using new Python packages for Azure
- Analyze the information returned from the service

[Go to lab](9-azure-cognitive-services/README.md)


## Explore Azure Database for PostgreSQL with Python

In this lab, you will learn how to import data into an Azure Database for PostgreSQL instance using a python script and the `psycopg2` module. You will learn to:

- Connect to an Azure Database for PostgreSQL
- Use the `psycopg2` to load and query data in the database.

[Go to lab](4-postgres/README.md)


## Number Facts with Python Web Apps

In this lab, you will deploy a python app to App Service using the Azure CLI.

- Use `az webapp up` to quickly provision Azure resources and deploy your app to Azure App Service.
- Leverage the `local context` feature of Azure CLI to ease management operations.

[Go to lab](9-azure-web-apps/README.md)


## Developing a Django + PostgreSQL application in a Dev Container

Work in a dev container using Visual Studio Code

- Open existing dev container in VS Code with the Remote - Container extension
- Build a React front-end
- Initialize a PostgreSQL database
- Run a Django app

[Go to lab](9-vscode-django-postgres-dev-container/README.md)


## Debugging a Flask App with WSL in VS Code 

Work with a Flask application using WSL in VS Code.
- Run/debug the Flask app
- Configure application tests
- Run application tests 

[Go to lab](9-windows-subsystem-for-linux/README.md)


## Use Hyperscale (Citus) to speed up analytics

This workshop is meant to be an introduction to Azure Database for PostgreSQL Hyperscale (Citus). First, you will create a cluster to scale out PostgreSQL and turn it into a distributed database. Then, you will create a schema and tables, load test data, and create a rollup function to massively speed up your query workload.

[Go to lab](4-postgres-citus/README.md)
