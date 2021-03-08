# Spaced repetition API

## Links

- Live Deployment: https://spaced-repetition-client-jet.vercel.app/
- Server Repository: https://github.com/cmgrace/spaced-repetition-api
- Client Repository: https://github.com/cmgrace/spaced-repetition-client

## Summary

This is a language learning application using the Spaced Repetition learning technique!

## Endpoints

### /api/user

### /api/auth

- POST requests authorization
- Used for logging in and register

### /api/language

- GET requests
- this endpoint returns a list of a user's languages, and the words being studied in that language

### /api/language/head

- GET requests
- This endpoint will return the next word to be studied

### /api/language/guess

- Users can POST their guess to each word as displayed in the /head endpoint, and receive feedback based on their response.
- User's guess determines the position where the word will be placed in the list

## Technology Used

### Client:

- ReactJS
- react-router-dom for routing and in-app navigation
- CSS (vanilla CSS)
- Babel
- Webpack
- Vercel for deployment
- Cypress for testing

### Backend:

- Express for handling API requests
- NodeJS for interacting with the file system
- Postgrator for database migration
- Mocha, Chai, Supertest for endpoints testing
- Knex.js for interfacing with PostgreSQL database
- Heroku for database and server deployment
