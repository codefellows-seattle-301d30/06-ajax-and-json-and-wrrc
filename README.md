# Kilovolt Blog - Day 6

**Author**: Jose Reyes and Suzanne Richman

**Version**: 1.0.2 

## Overview
This product is designed to give users a consistent reading and navigation experience across mobile and desktop devices, with content ordered by most recent first and sortable by both author or category. Additionally, users who want to add articles to the blog may now do so and either publish immediately or review a draft. If they want they can use the JSON link at the bottom to add their new content to the blogArticles.js to be displayed on the main blog, as well. We wanted the user to load articles from an external source.

## Getting Started
The user would need to 
* Create index.html
* Get the icons from IcoMoon (including all related files and CSS).
* Get the normalize.css from github.com/necolas/normalize.css.
* Search and find images of bacon, baseball, and cats
* Add filler text.
* Build CSS files according to SMACSS methodology.
* Include link to jQuery library (CDN).
* Create the articles as objects within an array with consistent property values.
* Create a constructor function to make the article array accessible to the constructor's method.
* Use jQuery to access and clone HTML elements of the DOM and populate those elements with content from the article array.
* Create forEach loops to generate new object instances and then append them to the DOM.
* Create an array of objects to hold the content generation for the DOM for each object.
* Create a JS file to generate a more interactive view of the DOM (selecting authors, catagories and hiding/showing full articles as well as navigating the long page as if it was a multipage website).
* Add Handlebars library and use it to create a tempalte for the HTML articles. 
* Add the Higlight JS library and related CSS styling to have the ability to highlight content.
* Create a new HTML page to handle article submissions that offers a form to create an article and ability to preview content.
* Connect the new HTML page to the exisiting blog page and update articleView.js, as well as articles.js to render content correctly across both pages.
* Be sure to write DRY code and leverage the libraries, as well as arrow functions to make code work as optimially as possible.
* Regularly use console logs, Chrome developer console tools and the help of others to identify and correct all coding and rendering erros. 
* Convert the blogArticle.js to JSON file.
* Then we used the AJAX methodology to access the article data in the JSON and store in Local Storage. 


## Architecture
I used IcoMoon icon font for navigation icons. I included the jQuery, Handlebars, Hightlight JS, and Railcasts libraies, with related CSS as needed. Applied AJAX function RESTful website application. I used Chrome to analyze and inspect. Project is built used HTML, CSS and JavaScript.```

## Change Log
02-20-2018 
10:42am - Commit built out our version of starter code, proofed files, inserted JS script in HTML to generate articles, store them in localStorage and get them form local storage if already present. Also finished the articleView functions to check/get local storage data. Created README.

12:50 - last commit, all code reviewed and Zombie code removed. Updated README.

02-22-2018 1:30pm - Resubmitting with a fix for the error of the page not reloading when localStorage is cleared. 

## Credits and Collaborations
* Thanks to my instructors and TAs and our classmates 
* The following libraries were used: jQuery,Highlight JS, Handlebars and Railcast.
* We referenced the jQuery cheat sheet: https://oscarotero.com/jquery/
* We used HandleBars library.
* We referenced our text book: Jon Duckett - JavaScript and JQuery.
* Reference for ternary from MDN: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator

* Reference for local storage -https://stackoverflow.com/questions/2010892/storing-objects-in-html5-localstorage
* Reference for arrow functions MDN- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions
* Special thanks to Josiah Green for reviewing my fetchAll function with me.