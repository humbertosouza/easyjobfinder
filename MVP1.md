# MVP 1

The product has the following main components:

* Crawler via APIs and webscrapping 
* Bigdata batch processing
* REST API for client application
* UX via Mobile application

## Proposed app/responsible site design

General App look and feel:
 
![App wireframe1](https://github.com/humbertosouza/easyjobfinder/blob/master/documentation/app-croquis-v01.png)

For login, a generic screen with sign in or sign up is expected.
Once signed in, it is expected that the user uploads his resume, main keywords and the city where she or he would like to work

Once she or he finishes, it is expected that she or he have a list of selected position title, company having a link to an URLs to the original site.

## Proposed AWS Cloud environment

![AWS Blueprint](https://github.com/humbertosouza/easyjobfinder/blob/master/documentation/Emploid-mvp1.jpg)

## First tasks

* Understand LinkedIn and Glassdoor API s and limitations
* Define the cloud or partner infrastructure where the project will be stored - Defined - AWS
* Define the size of the moving window, in months: consider positions open from today to 1,2, 3 months. Defined: 1 month? 
* Define the database to store the acquired data (Neo4G, Azure-Postgree, AWS-Postgree, MongoDB,?) - Defined - CSV files on S3 buckets
* Define the core system for processing inputs and outputs - Defined - Python
* Design the API (Java/Spring, Python/ Flask, ? ) - TBD
* Define the technology for the front-end application (Ionic, React,?) - TBD
* Wireframe the mobile application - Done

