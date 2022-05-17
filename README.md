# MERN_Solid_Book_Search

## GitHub 
The URL of the GitHub repository
https://github.com/Darigay/MERN_Solid_Book_Search

## Deployed Application
https://cryptic-beyond-55866.herokuapp.com/

## Table of Contents
- Description
- Usage
- Technologies
- Dependencies
- Screenshots
- Resources
- Contact

## Description:
This fully functioning Google Books API search engine built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API used for searching any book from GoogleBooks API, saving the books you like and deleting from the list.
This Heroku deployed application uses Apollo Server to use GraphQL queries and mutations to fetch and modify data, .authentication middleware works in the GraphQL API and an Apollo Provider communicate with an Apollo Server.

## Usage
- When the User clicks the application, it load the search engine.
- User is presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.
- When the user clicks on the Search for Books menu option, presented with an input field to search for books and a submit button.
- When the user not logged in and enter a search term in the input field and click the submit button, they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site.
- When the user clicks on the Login/Signup menu option, a modal appears on the screen with a toggle between the option to log in or sign up. On clicking the toggle is set to Signup , the user is presented with three inputs for a username, an email address, and a password, and a signup button. On clicking the toggle is set to Login, the user is presented with two inputs for an email address and a password and login button.
- When the user enters a valid email address and create a password and click on the signup button , user account is created and user is logged in to the site.
- When I am logged in to the site, the menu options change to Search for Books, an option to see my saved books, and Logout. After logging in and enter a search term in the input field and click the submit button ,the search results are featured with book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book and book information to User account upon clicking Save button on a book.
- Onclick on the option of "saved books", the user is presented with all of the books I have saved to account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account, onclicking the Remove button on a book - the book is deleted from saved books list.
- Onclick, on the Logout button , the user is able to logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button again.

## Technologies
- Javascript
- Node.js
- npm packages
- MongoDb
- Github

## Dependencies
- CLI
- Express.js
- apollo-server-express
- bycrypt
- graphql
- jsonwebtoken
- Mongoose
- nodemon

## Screenshots



## Resources
- UofU BootCamp MERN Modules
- MongoDb Documentation
- GraphQl Documentation
- mongoose Documentation

## Contact
Email Address : divya.arigay@gmail.com 
Github: Darigay@github.com


© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
