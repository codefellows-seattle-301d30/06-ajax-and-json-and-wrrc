# Kilovolt Blog

**Author**: Jennifer Williams Piper and Ramon Mendoza
**Version**: 1.0.0

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->

This is a fun website containing a blog with content that is appealing to the user,and easy to use, to entice the user to come back regularly. It should also ensure that the user has a similar experience on desktop and mobile devices, and allows the user to filter articles by author or category.
The user can add new blog articles by filling out a form. The app converts the content to JSON, and the user can cut and paste the JSON into blogArticles.js to create a new article.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
* Get starter code from this repo: https://github.com/codefellows-seattle-301d30/06-ajax-and-json-and-wrrc

* Update new.html and articleView.js to display form allowing creating of a new blog article using a duplicate of the same Handlebars template used in index.html.


## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
Uses HTML, CSS, JavaScript (ES6), jQuery, Markdown.
Uses Handlebars library to dynamically render templates.

Articles are fetched from file hackerIpsum.json.  The data is added to local storage and rendered on the page. On second and later page refreshes, the data is fetched from localStorage instead of fetched again from the file. Articles are appended to the DOM using jQuery traversal and setter methods in article.js.  Each article displays author, title, link to author page, time since publication, and blog entry. articleView.js contains code to populate author and category filters, and show or hide appropriate articles depending on user input.

## Change Log
2018-02-20 11:25am - Added starter code, successfully fetched data.
2018-02-20 11:40am - Complete fetchAll function to get data from localStorage and send it to loadAll function.
2018-02-20 11:51am - adjust order of function calls so articles render on page. Answer comments questions

2018-02-20 12:15pm -  Add to fetchAll function to send data to loadAll and refresh page when there was no local storage to start

2018-02-20 1:00pm - Update README.



## Credits and Collaborations

* Starter code from: https://github.com/codefellows-seattle-301d30/06-ajax-and-json-and-wrrc
* Handlebars CDN from https://cdnjs.cloudflare.com/ajax/libs/handlebars.js/4.0.11/handlebars.min.js
