# Overview
This README file provides information about the Internet Banking Website project. The project aims to create a secure and user-friendly Internet banking platform for customers to manage their accounts, perform transactions, and access financial services online. It is primarily built using HTML, CSS, and JavaScript.

# Easy_Cash_Banking
This online banking static web application provides the proper template of an actual website along with chatbot functionality.
This website contains four pages:
* Home page: This is the introductory page of the website.
* service: This page shows all the available services of the application.
* About: This page contains all basic understanding About applications and services.
* Contact: Customer can contact the bank and put their queries here.
* Bot service: Chatbot for customers' instant queries.

This project is a static website for Internet banking purposes that allows bank customers to fulfill their banking needs with ease and from any device.
From opening an account in the bank to accessing online business, all your needs can be fulfilled here.

# Prerequisites
Before getting started with the project, ensure you have a basic web development environment set up. You'll need:

* A web browser for testing and preview.
* A text editor or integrated development environment (IDE) for code editing.

# Project link(deployed using Azure)
[online_Easy_cash](https://ambitious-hill-05e999f10.3.azurestaticapps.net)

# Azure services used
* Static Web Apps (Azure App Services)
* Azure language service (custom question answering)

# What are Microsoft Azure web app services
Azure App Service is an HTTP-based service hosting web applications, REST APIs, and mobile backends. You can develop in your favorite programming language or framework. Applications run and scale with ease on both Windows and Linux-based environments.

![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/3bb9a27c-2c35-4d22-bfa4-151e0607d2cc)


## Continuous integration/deployment support
### Automated deployment
Automated deployment, or continuous deployment, is a process used to push out new features and bug fixes in a fast and repetitive pattern with minimal effect on end users.

Azure supports automated deployment directly from several sources. The following options are available:

#### Azure DevOps Services: 
You can push your code to Azure DevOps Services, build your code in the cloud, run the tests, generate a release from the code, and finally, push your code to an Azure Web App.
#### GitHub:
Azure supports automated deployment directly from GitHub. When you connect your GitHub repository to Azure for automated deployment, any changes you push to your production branch on GitHub are automatically deployed for you.
#### Bitbucket:
With its similarities to GitHub, you can configure an automated deployment with Bitbucket.

### Manual deployment
There are a few options that you can use to manually push your code to Azure:

#### Git:
App Service web apps feature a Git URL that you can add as a remote repository. Pushing to the remote repository deploys your app.
#### CLI:
web app up is a feature of the az command-line interface that packages your app and deploys it. Unlike other deployment methods, az webapp up can create a new App Service web app for you if you haven't already created one.
#### Zip deploy:
Use curl or a similar HTTP utility to send a ZIP of your application files to App Service.
#### FTP/S:
FTP or FTPS is a traditional way of pushing your code to many hosting environments, including App Service.

![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/39e91a83-4c26-4ad6-a9e0-cbd8a582c404)


## Deployment slots
When you deploy your web app you can use a separate deployment slot instead of the default production slot when you're running in the Standard App Service Plan tier or better. Deployment slots are live apps with their own host names. App content and configuration elements can be swapped between two deployment slots, including the production slot.

![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/feaace06-bbad-44e4-baf5-9b041f5c222a)


# Azure language services
Azure Language Services is a suite of cloud-based artificial intelligence (AI) and natural language processing (NLP) tools and services offered by Microsoft Azure. These services are designed to help developers build applications that can understand, interpret, and generate human language. Azure Language Services provides a wide range of capabilities for text analysis and language understanding.

## Azure language studio:
Azure Language Studio provides a well-settled platform for Azure Language services where we can easily manage our multiple language projects.

![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/9e631909-ed97-4bcf-9524-afe11b5f3a0d)

## Azure custom question-answering service:
The Azure AI-Language service includes a question-answering capability, which enables you to define a knowledge base of question-and-answer pairs that can be queried using natural language input. The knowledge base can be published to a REST endpoint and consumed by client applications, commonly bots.
The knowledge base can be created from existing sources, including:

* Websites containing frequently asked question (FAQ) documentation.
* Files containing structured text, such as brochures or user guides.
* Built-in chit-chat question and answer pairs that encapsulate common conversational exchanges.

![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/7e243f55-c2c6-4766-b985-e67da87bfec2)

## Create a knowledge base:
Add one or more data sources to populate the knowledge base:

* URLs for web pages containing FAQs.
* Files containing structured text from which questions and answers can be derived.
* Pre-defined chit-chat datasets that include common conversational questions and responses in a specified style.
![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/a46c10b0-bffe-45ed-881c-f2f85bca84c2)
![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/076cf98f-4fb8-4564-8d1b-b007a9677acb)
![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/4d6835c6-d175-4efb-99e2-5866d999742c)

## Question answering Bot:
While you can use a question-answering knowledge store in any sort of application, they are commonly used to support bots.

A bot is a conversational application that enables users to interact using natural language through one or more channels, such as email, web chat, voice messaging, or social media platform such as Microsoft Teams.

![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/16951b6c-2455-4708-86d4-5b86cc0f4921)

## Test in web chat:
![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/ca66efd1-c24b-463f-8940-f725f974ff91)


## Available bot service on your website
![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/9a70b4f7-db23-4d3e-9aae-a6813bf803f8)

I used web chat embedded code in my website to avail myself of the bot service to the customers.

![image](https://github.com/atharv-khede/Easy_Cash_Banking/assets/108985818/4c92ecba-b7a3-455b-8534-5b638cb94026)









 # Technology/tools used
* Microsoft Azure App services, Microsoft Azure language services
* HTML, CSS, JS
* GitHub
* Microsoft VS Code

# Accounts
* GitHub: [atharv-khede](https://github.com/atharv-khede)
* Azure Account Id: atharvkhede625@outlook.com
  
