# Node.js Assignment

Problem Statement: Use the provided sample data to load your Database. Please refer to sample data file “sample_data.json”. This file is attached separately.

You must fetch the following data using the API and display it on the frontend in a table format:

1. Users who have income lower than $5 USD and have a car of brand “BMW” or “Mercedes”.
2. Male Users who have phone price greater than 10,000.
3. Users whose last name starts with “M” and has a quote character length greater than 15 and email includes his/her last name.
4. Users who have a car of brand “BMW”, “Mercedes” or “Audi” and whose email does not include any digit.
5. Show the data of top 10 cities which have the highest number of users and their average income.

## Documentation

We can assume key for each query above to be indexs for :

`requestId` = [0,1,2,3,4,5]

### API Documentation

- API-ROUTE : `BASE_URL`/api/`:requestId`
- `requestId` as `[0,4]` represents the query data to be fetched from above problem statement
- `requestId` as `5` gives all the data

## Installation

Install Code-Editor with npm

```bash
  git clone https://github.com/amantyagi22/Task.git
  cd Task
```

- Root folder will have two folders client (Frontend), server (Backend)

Setup frontend (client side)

```bash
  cd client
  yarn
  yarn dev
```

Setup backend (client side)

```bash
  cd server
  yarn
  yarn dev
```

- We should add `.env` file to `.gitignore` but for your ease I'm not adding it.
- You can also use `npm` instead of `yarn`, just use `npm install` and after than `npm run dev`.

## Extra Skills

- I'm currently working with Next.js, Node.js with Typescript and MongoDB as the database.
- I used mongoimport for importing the sample.json data to MongoDB database.
