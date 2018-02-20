# Kilovolt Blog - Lab 06
#Author: Haron and Carl Olson 

# Version: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

# Overview
This product is designed to give users a consistent reading and navigation experience across mobile and desktop devices, with content ordered by most recent first and sortable by both author or category.

# Getting Started
The user would need to

Create index.html
Get the icons from IcoMoon
Get the normalize.css from github.com/necolas/normalize.css
Search and find images of bacon, baseball, and cats
Add filler text
Build CSS files according to SMACSS methodology
Include link to jQuery library (CDN)
Create the articles as objects within an array with consistent property values
Create a constructor function to make the article array accessible to the constructor's method
Create forEach loops to generate new object instances and then append them to the DOM
Create an array of objects from JSON data to hold the content generation for the DOM for each object.
Create a JS file to generate a more interactive view of the DOM (selecting authors, catagories and hiding/showing full articles as well as navigating the long page as if it was a multipage website).
Add Handlebars library and use it to create a tempalte for the HTML articles.

# Architecture
We used IcoMoon icon font for navigation icons. We included the jQuery and Handlebars libraies We used Chrome to analyze and inspect. Project is built on HTML, CSS and JavaScript.

Change Log
02-20-2018 9:45 am - Reviewed starter-code and completed comments. Also Psuedo coded our problem domain.

02-20-2018 10:45 am -  We decided to attempt loading our JSON data into local storage. So we can then access it in our loadAll().

02-20-2018 11:30 am - We have data in local storage. Now now needed to figure out how we can make the data run through our constructor function Articles.

02-20-2018 12:05 pm - We got the data to run through our constructor using the .then method to insure the correct order of code loading. Also initiated our fetchAll function on index so it runs on page load. 

# Credits
We used the jQuery library.
We referenced the jQuery cheat sheet: https://oscarotero.com/jquery/
We used HandleBars library.
We used a normalize.css file found here: github.com/necolas/normalize.css
We referenced MDN for array methods: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/prototype
We referenced our text book: Jon Duckett - JavaScript and JQuery.