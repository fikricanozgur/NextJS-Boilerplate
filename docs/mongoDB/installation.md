---
layout: default
parent: Mongo DB
title: Installation
nav_order: 1
has_children: false
---

## Installation

  1. You need to set up a MongoDB database. This could be on MongoDB Atlas, which is a cloud-hosted MongoDB service, or you could set up your own MongoDB server. Follow the setup steps. 
  1. Once your MongoDB database is set up, create a user with appropriate permissions. Make sure this user has the necessary privileges to perform CRUD operations on your database. You will achieve this during the default setup process.
  1. In MongoDB Atlas, for example, you can get the connection URI by navigating to your cluster and clicking on the "Connect" button. From there, you'll be given a connection string that includes the username, password, host, port, and database name such as mongodb+srv://nextjsboilerplate:<password>@cluster0.oo87vjp.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0. Do not forget to insert your username. 
  1. It's best practice to store sensitive information like database URIs in environment variables rather than hardcoding them into your code.



