# BOOKS APP

## Description

This is an app which I used to learn about GraphQL for NodeJS and ReactJS.
You can visit this app via :

## To run this

npm install

### Dev Environment

mkdir ./config

cd config

create your dev.env with MONGODB_URL and PORT

npm run dev

### Prod Environment

npm start

### GraphiQL

go to http://localhost:5000/graphql

## Project Overview

### Client

- ReactJS
- Apolo GraphQL

### Server (with GraphiQL)

- NodeJS
- Express + GraphQL

#### GraphQL Queries and Mutations

##### Queries

- books
- book(id)
- authors
- author(id)

##### Mutations

- addBook(name, genre, authorId)
- addAuthor(name, age)

### Database

- MongoDB

## My appreciation

Thank [The Net Ninja](https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg) for his [GraphQL Tutorial](https://www.youtube.com/watch?v=Y0lDGjwRYKw&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f&index=1)
