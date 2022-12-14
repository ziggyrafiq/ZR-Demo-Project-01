# ZR Demo Project 01

| Author   |Ziggy Rafiq (<https://ziggyrafiq.com> )|
|----------|-------------|
|__Version__ |__0.0.1__|

   



## Overview

This fictional store provides very simple Create, Read, Update and Delete functionality (CRUD). An API is generated using Swagger, and the development environment includes a Swagger UI for testing.

  **It is important to note that this project is not a complete application, which requires Microsoft Visual Studio 2022 or Microsoft Visual Studio Code.**

A simple REST API was built using the Unit of Work with the Repository pattern. 

A Requirements Markdown file [REQUIRMENTS.md] and an Open API Yaml script are included  as following
- The Requirements document [REQUIRMENTS.md](REQUIRMENTS.md)
- The OPen API Yaml Script file [books.openapi.yaml](books.openapi.yaml)


The diagram below illustrates how the REST API works with ASP.net Core, .net framework 6, Entity Framework Core, Swagger, MS SQL Database and Generic Repository Pattern, and demonstrates the benefits of using this pattern.
![Overivew Diagram of ZR Demo Project 01](/ZR.Documentation/ZR-Demo-Project-01-Overview.jpg)




## Solution Structure 
Here is the section of the document that explains how I have set up the project and the system architecture of the project using Visual Studio 2022.

### ZR.Api
***[Still Need to Write Here ]***

### ZR.Business
***[Still Need to Write Here ]***

### ZR.Infrastructure
***[Still Need to Write Here ]***

### ZR.Infrastructure.Migrations
***[Still Need to Write Here ]***


### Steps to Excute the Dev Build Project

<code>Add-Migration BuildZRProjectDatabase -Project  ZR.Infrastructure.Migrations</code>
and then you will need to apply the Migration, which is generated by Visual Studio 
<code>Update-Database</code>


## Project on GitHub
The project source code can be found on my GitHub account, which is listed below. Please click on the link to access my GitHub account repository. 

**https://github.com/ziggyrafiq/ZR-Demo-Project-01** 
