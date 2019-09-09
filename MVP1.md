# MVP 1

The product has the following main components:

* Crawler via APIs and webscrapping 
* Bigdata batch processing
* REST API for client application
* UX via Mobile application

## Proposed app/responsible site design

General App look and feel:
 
![alt text][pic]

[pic]: https://github.com/humbertosouza/easyjobfinder/blob/master/documentation/app-croquis-v01.png  "App look"

For login, a generic screen with sign in or sign up is expected.
Once signed in, it is expected that the user uploads his resume, main keywords and the city where she or he would like to work

Once she or he finishes, it is expected that she or he have a list of selected position title, company having a link to an URLs to the original site.

## Proposed AWS Cloud environment

![alt text][pic]
[pic2]: https://github.com/humbertosouza/easyjobfinder/blob/master/documentation/Emploid-mvp1.jpg "AWS architecture"

## First tasks

* Understand LinkedIn and Glassdoor API s and limitations
* Define the cloud or partner infrastructure where the project will be stored (AWS, Azure, GCP, partner,?)
* Define the size of the moving window, in months: consider positions open from today to 1,2 or 3 months? 
* Define the database to store the acquired data (Neo4G, Azure-Postgree, AWS-Postgree, MongoDB,?)
* Define the core system for processing inputs and outputs (Python ?)
* Design the API (Java/Spring, Python/ Flask, ? )
* Define the technology for the front-end application (Ionic, React,?)
* Wireframe the mobile application - Done

