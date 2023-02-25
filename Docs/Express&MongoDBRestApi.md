# What is a Rest API

A Rest API is split into 2 sections.

1. Rest Client
2. Rest Server

We use a Rest API to perform CRUD actions.

## Create

Rest Client --> HTTP POST ( Path + Payload ) --> Rest Server
Rest Client <-- Returns a 201 Response <-- Rest Server

## Read

Rest Client --> HTTP GET ( Path ) --> Rest Server
Rest Client <-- Returns a 200 + Payload <-- Rest Server

## Update

Rest Client --> HTTP PUT ( Path + id + Payload ) --> Rest Server
Rest Client <-- Returns a 200 Response <-- Rest Server

## Delete

Rest Client --> HTTP DELETE ( Path + id ) --> Rest Server
Rest Client <-- Returns a 200 Response <-- Rest Server

# Setup

In this build we will be using

-   express
-   dotenv ( use enviroment variables )
-   mongoose ( DB )
-   colors ( Color the terminal )

In the tutorial they install nodemon as a dev dependancy, however we can just use the --watch flag now
