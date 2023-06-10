# Text-Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The web text editor is an application that empowers users to generate notes or code snippets, regardless of their internet connectivity. It provides a dependable means to retrieve and access these entries at a later time. By leveraging integrated service worker and Cache API's, the application remains fully operational even when the internet connection is inactive. Users can effortlessly access previously visited pages even in offline mode.


The URL of the GitHub repository is https://github.com/JLoya900/Text-Editor and the repository name is Text Editor.

🚀The application has been deployed to Heroku and the URL of the deployed application is:-
 
https://joaquin-loya-80466.herokuapp.com/

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [References](#references)
* [License](#license)

## Installation

* This text editor necessitates the implementation of various methods and the storage of data in an IndexedDB database during its development process.

* This application will require the installation of Node.js and various npm packages.

*   Node Package Manager (npm) is a sophisticated software manager and installer that facilitates the seamless integration of modules into a Node.js project. It not only ensures the proper placement of these modules for utilization but also adeptly manages any conflicts arising from dependencies. The initialization process for npm begins with the command **npm init**, resulting in the generation of a comprehensive package.json file. This file encapsulates all the pertinent application details provided by the user during the npm initialization phase.


* The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.       

## Usage

1.
``````    
GIVEN a text editor web application, 
WHEN I open my application in my editor
THEN I should see a client server folder structure
``````
*Below is the screenshot of the client server folder structure.  The folder structure have been set up or given in this structure.*


2.
``````
    WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file
``````
*Below is the screenshot of the running at npm run start and npm run build* 

![alt text](/assets/img01.png)

3.
``````
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
``````
*Below is the screenshot of the text editor "Just Another Text Editor (J.A.T.E)"*

![alt text](/assets/img02.png)

4.
``````
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
``````
*Below is the  screenshot of content in the text editor has been retrieved from the IndexedDB"*

![alt text](/assets/img05.png)

5.
``````
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
``````
*Below is the screenshot of icon on the desktop"*

![alt text](/assets/img04.png)


6.
``````
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
``````
*Below is the screenshot of the static assets"*

![alt text](/assets/img07.png)
7.

 ````````
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application 
````````
![alt text](/assets/img02.png)

## References

*   Module 19 Mini-Project
*   Request-Response : The Full-Stack Blog : Heroku Deployment Guide
 
## License

This project is licensed under the terms of the MIT license.