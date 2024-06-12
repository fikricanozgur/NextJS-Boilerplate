---
layout: default
parent: Prisma & Mongo DB
title: Installation
nav_order: 1
has_children: false
---

## Create MongoDB Account

1. You need to set up a MongoDB database. This could be on MongoDB Atlas, which is a cloud-hosted MongoDB service, or you could set up your own MongoDB server. 
1. Once your MongoDB database is set up, create a user with appropriate permissions. Make sure this user has the necessary privileges to perform CRUD operations on your database. You will achieve this during the default setup process.
1. In MongoDB Atlas, for example, you can get the connection URI by navigating to your cluster and clicking on the "Connect" button. From there, you'll be given a connection string that includes the username, password, host, port, and database name. Fill in your credentials and other missing data into the connection string. 
1. It's best practice to store sensitive information like database URIs in environment variables rather than hardcoding them into your code. Save yours in the .env file. 

## Installation

Follow the below steps:

```console
user@nextjs_boilerplate:~$ npm install mongodb
user@nextjs_boilerplate:~$ npm install include--dev prisma
user@nextjs_boilerplate:~$ npx prisma init

// Make sure to add .env to .gitignore
// Create and populate prisma/schema.prisma file

user@nextjs_boilerplate:~$ npx prisma db push
user@nextjs_boilerplate:~$ npx install @prisma/client
user@nextjs_boilerplate:~$ npx prisma generate
```
