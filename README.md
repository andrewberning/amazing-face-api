# Amazing Face API - Back End Server

This is the back end of my Amazing Face app.
It detects faces in images that are uploaded to it, via the image URL, by using the face-recognition API from Clarifai. 
It also keeps track of how many images you have uploaded in your account.
Yes, your own login account. AMAZING RIGHT?!

## Dependencies and Packages

express, nodemon, knex, clarifai, bcrypt, cors, dotenv, and pg

## Installation

1. Clone this repo
2. Use 'npm install' to install all the necessary dependencies.

## Things to add
Create a '.env' file and add the following:
 - API_KEY: Your own api key from Clarifai (e.g. '2dfijk49kser1')
 - PORT: Any port you want (e.g. 3000)



## License

[MIT](https://choosealicense.com/licenses/mit/)
