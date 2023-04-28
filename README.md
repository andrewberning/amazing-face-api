# Amazing Face API

This is the back-end of my Amazing Face app. It handles requests from my front-end, to the server, to the database and sends a response back to the client.

## How did you build it?

I built the server using Node.js with the express.js framework. I used postgreSQL for my database and connected it to my server.

## Dependencies and Packages

- [express](https://expressjs.com/en/starter/installing.html)
- [nodemon](https://www.npmjs.com/package/nodemon)
- [knex](https://knexjs.org/guide/)
- [pg](https://www.npmjs.com/package/pg)
- [clarifai](https://github.com/Clarifai/clarifai-javascript#basic-use)
- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [cors](https://www.npmjs.com/package/cors)
- [dotenv](https://www.npmjs.com/package/dotenv)

## Installation

1. Clone this repo
2. Use 'npm install' to install all the necessary dependencies.

## Things to add
Create a '.env' file and add the following:
 - API_KEY: Your own api key from Clarifai (e.g. '2dfijk49kser1')
 - PORT: Any port you want (e.g. 3000)



## License

[MIT](https://choosealicense.com/licenses/mit/)
