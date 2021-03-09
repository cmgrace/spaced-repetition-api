# Spaced repetition API

## Links

- Live Deployment: https://spaced-repetition-client-jet.vercel.app/
- Client Repository: https://github.com/cmgrace/spaced-repetition-client

## Summary

This is a language learning application using the Spaced Repetition learning technique!

## Endpoints

### /api/user

- POST requests
- Used for register

### /api/auth

- POST requests authorization
- Used for logging in and register

### /api/language

- GET requests
- This endpoint returns a list of a user's languages, and the words being studied in that language

### /api/language/head

- GET requests
- This endpoint will return the next word to be studied

### /api/language/guess

- Users can POST their guess to each word as displayed in the /head endpoint, and receive feedback based on their response.
- User's guess determines the position where the word will be placed in the list

## Technology Used

### Frontend

- ReactJS
- React Router
- React Context
- HTML
- CSS
- Webpack
- Cypress for testing
- Deployed at Vercel

### Backend

- RESTful API
- Node & Express
- PostgresSQL
- Knex
- Supertest
- Mocha & Chai
- Deployed Heroku
