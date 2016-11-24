# MEAN-to-do
A simple To-Do list using MEAN stack.
Based on this tutorial:
https://scotch.io/tutorials/creating-a-single-page-todo-app-with-node-and-angular

## NodeJS part
`server.js` is the entry point to the application. It imports a bunch of libraries and starts a server.
`app/routes.js` is essentially a collection of APIs to GET, POST (create) and DELETE to-do items. They execute in order specified, so the bottom GET route specifies that a request to any other URL should be server with the index.html page.
`app/models/todo.js` defines a model for a to-do item.
`config/database.js` defines the MongoDB connection.

## Angular part
`app` folder contains all the Angular components. 
