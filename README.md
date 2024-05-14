# GraphQL API with Node.js, Prisma, Docker and Postgres

## Project description
This is a project from a [tutorial](https://dev.to/nditah/how-to-build-a-graphql-api-with-node-prisma-and-postgres-ajg) on how to build a GraphQL API with Node.js, Prisma, Docker and Postgres. The tutorial covers the following steps:

* Creating the Node.js project
* Defining the GraphQL schema
* Defining the GraphQL resolvers
* Creating the GraphQL server
* Setting up Prisma with PostgreSQL
* Defining the data model with Prisma * Migrate
* Using Prisma Client in the GraphQL resolvers
* Creating and migrating the PostgreSQL database
* Modifying the data model
* Testing the API

The project demonstrates how to use GraphQL with Node.js and Prisma ORM to interact with a PostgreSQL database running in a Docker container. It showcases the power of GraphQL in building flexible and efficient APIs, while leveraging Prisma's capabilities for database modeling, migrations, and type-safe data access.

## Build and run the project
To build and run the project, you need Docker on your local machine. First spin up the container for the postgres database by running `docker-compose up`. Then run `npx prisma migrate dev --name "init" ` and start the server with `npm run start` and then  Make sure you dont have another postgres database on your local machine because then the prisma will complain it cant find the database.

