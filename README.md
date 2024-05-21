# Note Taker App | Powered by Express.js, with JSON storage

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Description

If you've ever needed a platform to create and store notes, whether for personal organization, for your small business, household management, or another pursuit, this note-taker app is designed to meet that need. By navigating to the application in the browser, the user can create and save notes as JSON data using an attractive and intuitive user interface. One a note has been created, its title will show in the sidebar on the left, which can be clicked to display the note once again. A note can also be deleted by clicking the delete icon to the right of the note title in the sidebar. The app stays updated with the additions and deletions you have made, so that you're able to view and manage your notes with ease and accuracy. The app has an integrated frontend and backend, so the user is able to make GET, POST, and DELETE requests via their interaction with DOM elements rather than needing to rely on local storage in the browser or having to make manual calls to an API. (Although, users interested in Express.js, APIs, and HTTP request methods can make requests to various endpoints in platforms like Insomnia, if desired.) Feel free to read through the Installation, Usage, and Features sections to learn more about the app and how to get started!

## Table of Contents

[Installation](#installation)

[Usage](#usage)

[Features](#features)

[Contributing](#contributing)

[Credits](#credits)

[Questions](#questions)

[License](#license)

## Installation

Installation: no installation is needed to use this application—simply navigate to the deployed site at [https://note-taker-app-9s40.onrender.com/](https://note-taker-app-9s40.onrender.com/). When you navigate to the site, Render will manage the environmental variables and web services behind the scenes to provide access the app.

## Usage

Upon navigating to [https://note-taker-app-9s40.onrender.com/](https://note-taker-app-9s40.onrender.com/), the user will see the home page, entitled Note Taker 📝 Take notes with Express, as well as a "Get Started" button. When the user clicks the "Get Started" button, they will be routed to the notes page at [https://note-taker-app-9s40.onrender.com/notes](https://note-taker-app-9s40.onrender.com/notes). Here, the user can enter notes in the form on the right, view any previously saved notes by clicking the note title in the left sidebar, and delete notes by clicking the note's delete icon in the left sidebar.  

## Features

Follow along with the screenshots and descriptions to see the application in action.

The home page has the following appearance, which helps to communicate the purpose of the application and welcome the user to the site. 

![screenshot1](//assets/Screenshot1.png)

Assuming there are no saved notes, when the user clicks the "Get Started" button and visits the notes page, the page will have the following appearance.

![screenshot2](//assets/Screenshot2.png)

To create a note, the user will enter the note title in the input element with the placeholder text "Note Title" and enter the content of the note in the textarea element with the placeholder text "Note Text". A "Clear Form" button will appear once any text has been added to either element, and a "Save Note" button will appear once text has been added to both elements. If the user decides they would like to discard the note, they can click the "Clear Form" button to do so. Once the title and note text have been fully entered, the user can click the "Save Note" button to save the note. The below screenshot shows a sample note a small business owner might create. 

![screenshot3](//assets/Screenshot3.png)

After clicking the "Save Note" button, the title of the note will appear in the sidebar on the left, as shown in the following screenshot. 

![screenshot4](//assets/Screenshot4.png)

To view the note again, the user can click the note title in the sidebar—this will cause the saved note to be displayed on the right hand side.

![screenshot5](//assets/Screenshot5.png)

Notes can also be deleted by clicking the red delete icon to the right of the note title in the sidebar. To see the dynamic, responsive nature of the application while in use, reference the below GIFs. The first GIF shows how the note displayed on the right changes when toggling between note titles in the sidebar. The second GIF shows notes being deleted on click of the delete icon.

![gif1](//assets/Gif1.gif)

![gif2](//assets/Gif2.gif)

If you would like to learn more about how user interactions with frontend DOM elements trigger the appropriate backend responses, feel free to take a look at the comments in the server.js and index.js files. To learn more about Render, the web hosting solution which hosts this application, visit Render's website [here](https://docs.render.com/).

## Contributing

If you would like to contribute, feel free to email me at thornburg.rebeca1@gmail.com with any ideas on new features or improved functionality, create an Issue, or submit a pull request. If you create an issue, please @ me. If you would like to make a pull request, please request a pull request review from me so that I can review your proposed changes. I look forward to collaborating with you!

## Credits

I would not be able to do this without the help of my instructor and TA through the DU Fullstack Bootcamp. Them, along with my fellow students were able to answer several of my questions and help me trouble shoot. 

Geeks for Geeks. (2023, October 11). JavaScript program to find index of an object by key and value in an array. GeeksforGeeks. https://www.geeksforgeeks.org/javascript-program-to-find-index-of-an-object-by-key-and-value-in-an-array/ (Referenced when brainstorming how to design the DELETE route)

MDN Web Docs. (2023, June 29). await - JavaScript. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await

Stack Overflow. (2020, December 3). While executing app.js it gives an error in console. Stack Overflow. https://stackoverflow.com/questions/65110922/while-executing-app-js-it-gives-an-error-in-console (Referenced for help using MersenneTwister19937 of npm package random-js)

Stack Overflow. (2021, July 8). Node Express- delete route works but throws an error. Stack Overflow. https://stackoverflow.com/questions/68306196/node-express-delete-route-works-but-throws-an-error (Referenced when creating the DELETE route)

Stack Overflow. (2023, July 20). What are express.json() and express.urlencoded()? Stack Overflow. https://stackoverflow.com/questions/23259168/what-are-express-json-and-express-urlencoded (Referenced to better understand and explain express.json() and express.urlencoded())

## Questions

My GitHub username is Rthornburg-Ardi if you would like to connect or view my other projects. Feel free to reach out to me at https://github.com/Rthornburg-Ardi/ or sara.marie.hines1@gmail.com if you have any further questions about this project, and I'll be glad to assist.

## License

This project is covered under the MIT License. You can learn more about this license and its coverage and permissions [here](https://opensource.org/licenses/MIT).