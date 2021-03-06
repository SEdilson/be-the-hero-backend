# Be The Hero Backend

[![CircleCI](https://circleci.com/gh/SEdilson/be-the-hero-backend/tree/master.svg?style=svg)](https://circleci.com/gh/SEdilson/be-the-hero-backend/tree/master)


This is the backend of the project made at the Omnistack 11 week.

## Stack

This project uses:

- [NodeJS](https://nodejs.org)
- [Express](https://expressjs.com)
- [SQLite](https://www.sqlite.org)

## Running locally

To run this project locally follow these steps:

1 - Download or clone this repo:
```
    git clone https://github.com/SEdilson/be-the-hero-backend.git
```

2 - Install the dependencies:
```
    npm install
```

3 - Run the migrations:
```
    npx knex migrate:latest
```

4 - Run the app:
```
    npm run dev
```

5 - Go to:
```
    http://localhost:3333
```

6 - Run tests:
```
    npm test
```
