# [Budget Tracker 2022](#title)
​
## [Description](#description)
Budget Tracker 2022 is a simple web application to track financial transactions (deposits and withdrawls) and is available even when network connectivity is not. Transactions are stored in a MongoDB database (NoSQL) when you are online, but in the event you do't have connectivity, a service worker and indexDB make sure that uou can keep using the app and logging transactions. Once you are back oline, your transactions are automatically submitted to the database.

>> - Deployed Application URL: https://budget-2022.herokuapp.com/

![Repository Size](https://img.shields.io/github/repo-size/bkfleet1/budget-tracker-2022?style=plastic)
>> - Project Repository URL: https://github.com/bkfleet1/budget-tracker-2022

>> ![Budget Tracker 2022 Repository](/public/images/repository.png)
​
## Table of Contents
> - [Title](#title)
> - [Description](#description)
> - [Developer](#developer)
> - [Packages & Libraries](#resources)
> - [Tech Stack](#stack)
> - [Installation](#installation)
> - [Use Instructions](#usage)
> - [Tests](#tests)
> - [Questions](#questions)
​
​
## [Developer](#developer)
> * [Brad Kelley](mailto:bradkelleytech@gmail.com)


## [Packages & Libraries](#resources)

The following packages & libraries were used in the development of this project.
> - chart.js CDN (version ^2.8.0)
> - Compression (version ^1.7.4)
> - Bootsrap CDN (version ^4.7.0)
> - Express (version ^4.17.3)
> - MongoDB (version ^5.0.6) or MongoDB Atlas (cloud version ^5.0.6)
> - Mongoose (version ^6.2.9)
> - Morgan (version ^1.1.0)
> - Node.js (version ^16.14.2)


## [Tech Stack](#stack)
![80.4% Javascript](https://img.shields.io/badge/javascript-80.4%25-blue) ![14.9% HTML5](https://img.shields.io/badge/HTML5-14.9%25-blue) ![4.7% CSS](https://img.shields.io/badge/CSS-4.7%25-blue)

> - HTML5
> - JavaScript
> - CSS


## [Installation](#installation)

NOTE: This application requires Node.js (version ^16.14.2) and MongoDB. You can locally deploy the application using MongoDB (version ^5.0.6) locally or MongoDB Atlas (cloud version ^5.0.6) for access to your data anywhere. The installation instructions below do not describe how to install Node.js and MongoDB. Additionally, the instruction assume that you have successfully installed both applications prior to installing **Budget Tracker 2022**. You can download the latest versions of these Node.js and MongoDB from the following URLs:

> * [Node.js](https://nodejs.org/en/) - https://nodejs.org/en/

> * [MongoDB Community - Local Deployment](https://www.mongodb.com/try/download/community) - https://www.mongodb.com/try/download/community

> * [MongoDB Atlas - Cloud Deployment](https://www.mongodb.com/cloud/atlas/register2) - https://www.mongodb.com/cloud/atlas/register2

The following steps are required to execute the **Budget Tracker 2022** application.
> 1. Clone the repository located at: https://github.com/bkfleet1/social-network.
> 2. Open the project in a terminal application, such as git bash, and install NPM. To install **npm**, **Compression**, **Express**, **Mongoose**, and **Morgan** dependencies, simply type **npm install** and press enter. 


## [Use Instructions](#usage)
After the installation process, you are ready start the application server powered by Express. Just open the project in a terminal application, such as git bash, and type "**npm start**" and press enter. Your initialized application server should resemble the image below.

![Start Express Server](./images/express.png)

The application will create the **budget** database in MongoDB, which includes a single collection named **transactions**. The images below illustrate the the application's database running both locally using MongoDB (version ^5.0.6) as well MongoDB Atlas (cloud version ^5.0.6).

![MongoDB Community - Local Deployment](./images/mongodb1.png)

![MongoDB Atlas - Cloud Deployment](./images/mongodb2.png)




## [Tests](#tests)
No formal testing is available. 
​
## [Questions](#questions)
Please email the develop with any questions.

> * [Brad Kelley](mailto:bradkelleytech@gmail.com) 

