# Awesome Azure SQL resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated awesome list of resources for taking advantage of everything Azure SQL has to offer, useful for the beginners and the veterans.

## Getting started

- :tv: [Azure SQL for Beginners](https://www.youtube.com/playlist?list=PLlrxD0HtieHi5c9-i_Dnxw9vxBY-TqaeN&_lrsc=b0140d7c-6896-492f-a931-236cdf0858c8): 61 small videos to learn everything to get started

## Labs & Workshops

- :bar_chart: [sqlworkshops](https://aka.ms/sqlworkshops): Lab and Workshops on Azure SQL (and more)

## Microsoft Learn

- [Azure SQL Modules @ Microsoft Learn](https://docs.microsoft.com/en-us/learn/browse/?expanded=azure&products=azure-sql-database): all the Microsoft Learn modules related to Azure SQL. From security to development, from performances to maintenance.
- [Build Serverless Full Stack Apps on Azure](https://docs.microsoft.com/en-us/learn/paths/build-serverless-full-stack-apps-azure/): learn how to create, build, and deploy modern full stack applications in Azure by using the language of your choice (Python, Node.js, or .NET) and with a Vue.js frontend. Topics covered include modern database capabilities, CI/CD and DevOps, backend API development, REST, and more. 
- [Deploy IoT solutions with Azure SQL Database](https://docs.microsoft.com/en-us/learn/modules/deploy-iot-solution-azure-sql-database/): learn how Azure SQL Database provides a price-performant backend for IoT applications. You'll also deploy a template that includes Azure SQL Database, Azure VMs, Azure Functions, and Power BI which simplifies deploying and configuring IoT solutions.

## Community

- [Azure Data Community](https://www.microsoft.com/en-us/sql-server/community): list of user groups and community resources like events, recordings, blogs and so on.

## Code Samples

### Generic
- [Azure SQL DB Samples and Best Practices](https://github.com/yorek/azure-sql-db-samples): Samples and Best practices to use Azure SQL DB to build modern, mission critical applications, with ease and confidence
- [Azure SQL Hyperscale Autoscaler](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-hyperscale-autoscaler/azure-sql-hyperscale-autoscaler/): How to create a serverless solution to automatically scale Azure SQL Hyperscale, based on detected workload
- [TodoMVC Sample App Full Stack Implementation](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-todo-mvc/azure-sql-db-todo-mvc/)

### Big Data
- [Fast Data Loading in Azure SQL DB using Azure Databricks](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-databricks/azure-sql-db-databricks/): Samples and best practices on how use Azure SQL with Azure Databricks

### Change Stream
- [Azure SQL Change Stream with Debezium](https://github.com/Azure-Samples/azure-sql-db-change-stream-debezium): Set up a change stream from Azure SQL using the open source tool [Debezium](https://debezium.io/)

### Data Loading
- [Azure SQL DB Import Data Samples](https://github.com/Azure-Samples/azure-sql-db-import-data): Samples on how to import data (JSON, CSV, Flat-Files, etc) into Azure SQL
- [Fast Data Loading in Azure SQL DB using Azure Databricks](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-databricks/azure-sql-db-databricks/): Samples and best practices on how use Azure SQL with Azure Databricks

### DevOps
- [Azure SQL CI/CD Pipeline](https://github.com/Azure-Samples/azure-sql-db-ci-cd): A sample on how to deploy Azure SQL using the open source [DbUp](http://dbup.github.io/) and running test using [NUnit](https://nunit.org/)

### Geospatial
- [Monitor GeoFences in real-time using Azure SQL and Stream Analytics](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-serverless-geospatial-stream-analytics/azure-sql-db-serverless-geospatial-stream-analytics/)
- [Real-Time Serverless GeoSpatial Public Transportation GeoFencing Solution](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-serverless-geospatial/azure-sql-db-serverless-geospatial/)

### Graph
- [Million Song Dataset in Azure SQL DB / SQL Server](https://docs.microsoft.com/en-us/samples/azure-samples/millionsongdataset-sql/millionsongdataset-sql/): Using Graph object in Azure SQL with the Million Song dataset

## GraphQL
- [Azure SQL & GraphQL Samples](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-graphql/azure-sql-db-graphql/)
- [REST & GraphQL TodoMVC Sample App Full Stack Implementation with Prisma](https://github.com/Azure-Samples/azure-sql-db-prisma): Full-Stack End-To-End implementation - both with REST and GraphQL support - with Azure SQL and Prisma.io of the well-known To-do list sample.

### Streaming
- [Streaming at Scale](https://docs.microsoft.com/en-us/samples/azure-samples/streaming-at-scale/streaming-at-scale/): End-to-end solution to implement a streaming at scale scenario

### REST 
- [Creating a REST API with .NET Core and Azure SQL](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-dotnet-rest-api/azure-sql-db-dotnet-rest-api/)
- [Creating a REST API with Python and Azure SQL](https://github.com/Azure-Samples/azure-sql-db-python-rest-api/)
- [Todo Backend Implementation with Azure Functions, Node and Azure SQL](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-todo-backend-func-node/azure-sql-db-todo-backend-func-node/)
- [Using Change Tracking API to sync data between Apps and the Cloud](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-sync-api-change-tracking/azure-sql-db-dotnet-rest-api/)
- [Serverless REST API with Azure Functions, Node and Azure SQL](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-node-rest-api/azure-sql-db-node-rest-api/)
- [Creating API to securely access data using Azure SQL Row Level Security](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-secure-data-access-api/azure-sql-db-secure-data-access-api/)
- [REST & GraphQL TodoMVC Sample App Full Stack Implementation with Prisma](https://github.com/Azure-Samples/azure-sql-db-prisma): Full-Stack End-To-End implementation - both with REST and GraphQL support - with Azure SQL and Prisma.io of the well-known To-do list sample.

## Articles 

- [Bandwidth-friendly Query Profiling for Azure SQL Database](https://sqlperformance.com/2020/04/sql-performance/bandwidth-friendly-query-profiling-azure-sql-database): Using Extended Events to profile query execution
- [How to use batching to improve application performance](https://docs.microsoft.com/en-us/azure/azure-sql/performance-improve-use-batching): An explanation of batching techniques that can be used to improve performance by a lot
- [ScriptDOM Samples](https://github.com/arvindshmicrosoft/SQLScriptDomSamples): Samples on how to use the ScriptDOM parser to parse T-SQL statements

## Scripts

- [Azure SQL Diagnostic Queries](https://glennsqlperformance.com/resources/): Comprehensive diagnostic and health-check queries
- [Azure SQL Tips](https://aka.ms/sqldbtips): Get tips to improve database design, health, and performance right from the Azure SQL product group
- [sp_whoisactive](https://github.com/amachanic/sp_whoisactive): Comprehensive activity monitoring stored procedure

## Tools

- [Azure SQL Monitoring](https://github.com/denzilribeiro/sqldbmonitoring): Solution for near-realtime monitoring using Grafana and the Telegraf SQL plugin. 
- [Smart Bulk Copy](https://github.com/Azure-Samples/smartbulkcopy/tree/master/): High-Speed Bulk Copy tool to move data from one Azure SQL / SQL Server database to another

## DevOps
- :blue_book: [Azure SQL Database CI/CD Pipeline with GitHub Actions](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-ci-cd/azure-sql-db-ci-cd/): Official documentation
- :page_facing_up: [DevOps for Azure SQL](https://devblogs.microsoft.com/azure-sql/devops-for-azure-sql/): Everything you want to know around how to apply DevOps to databases, Azure SQL DB in particular
- :tv: [Getting Started with DevOps for Azure SQL](https://www.youtube.com/watch?v=j7OnxOz7YDY): What is Data DevOps and a discussion around the first option: migration based deployment
- :tv: [Using Azure Pipelines for Azure SQL Deployments](https://www.youtube.com/watch?v=G7H6HbzwAfs): Discussion state based deployment, and full demo on using Azure Pipelines to deploy the database 
- 📄 [Advanced automated deployment of Azure SQL Database with Azure DevOps](https://erikej.github.io/sqlserver/2021/01/11/azure-sql-advanced-deployment-part1.html): Detailed tutorial on how to deploy Azure SQL with Azure DevOps 

## Libraries 

### .NET

- [EF Core](https://docs.microsoft.com/en-us/ef/core/): Native .NET Core OR/M mapping tool. 
- [Dapper](https://github.com/StackExchange/Dapper): A simple object mapper for .Net
- [SqlKata](https://sqlkata.com/): A fluent SQL query builder for C#

### Node

- [node-mssql](https://www.npmjs.com/package/mssql): Microsoft SQL Server client for Node.js
- [Knex.js](https://knexjs.org/): "Batteries included" SQL query builder
- [Prisma](https://www.prisma.io/): Next-generation ORM for Node.js and TypeScript
- [Sequelize](https://sequelize.org/): A promise-based Node.js ORM

### Python

- [SQLAlchemy](https://www.sqlalchemy.org/): Python SQL toolkit and Object Relational Mapper

## Videos

- [Azure SQL for Beginners](https://www.youtube.com/playlist?list=PLlrxD0HtieHi5c9-i_Dnxw9vxBY-TqaeN&_lrsc=b0140d7c-6896-492f-a931-236cdf0858c8): 61 small videos to learn everything to get started
- [Data Exposed Playlist](https://www.youtube.com/playlist?list=PLlrxD0HtieHieV7Jls72yFPSKyGqycbZR): an ongoing series to learn everything about the Azure Data platform, Azure SQL included
- [Data Loading Best Practices on Azure SQL DB](Data Loading Best Practices on Azure SQL Database): 20 minutes video dedicate on the explanation on the best practices to load data into Azure SQL as fast as possibile
- [Create secure API with .NET, Dapper and Azure SQL](https://www.youtube.com/watch?v=TdvFYyLMHB0/): Live coding recording of development of a backend API with security, full CI/CD - test included and unexpected requirements, just like the real world. 

## Books

- [Practical Azure SQL Database for Modern Developers](https://www.apress.com/it/book/9781484263693): Building Applications in the Microsoft Cloud with Azure SQL
- [Azure SQL Revealed](https://www.apress.com/it/book/9781484259306): A Guide to the Cloud for SQL Server Professionals

## Blogs

### Official
- [Azure SQL Devs’ Corner](https://devblogs.microsoft.com/azure-sql/): Azure SQL team blog with focus on developers
- [Azure SQL @ TechCommunity](https://techcommunity.microsoft.com/t5/azure-sql/bg-p/AzureSQLBlog): Azure SQL team blog with focus on IT Pros