This project is a web application that allows users to search for breweries by city, name, or type using the Open Brewery DB API. Users can sign up, log in, search for breweries, view detailed brewery information, and add reviews. The application is built with a full stack architecture, utilizing a hosted database to store user reviews.


## Overview
This is a web application to search Brewery by City, Type, Name using Brewery APIs (https://www.openbrewerydb.org/documentation).

Users can provied ratings and add reviews.

## Features
- Users can create profile and ratings, reviews and browse nearby breweries.
- user can search based on City, Type, Name.
- Users can refer to other peoples ratings and reviews.

## TechStack
- NodeJS - Backend
- ExpressJS - Handeling routes
- ejs - Its a templating engine
- MongoDB - Store user review and Ratings
- MySQL - Store the signup and login details.

## How to Run
- ``` git clone https://github.com/sapnaacharya25/Brewery-Review-System ```
-   3rd party api ```https://www.openbrewerydb.org/documentation ```
- Installing all dependencies
   - ``` npm i ```
- To run server in Developer mode
  - ```npm run dev```
- To run server in Production mode
  - ``` npm run prod```
- To access the web application on the browser
  - [localhost:3000](http://localhost:3000) or use .env to set the port as required
