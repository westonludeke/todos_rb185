## Sinatra Todo App

### Description: 

A Todo Application built in Sinatra & Ruby backed by a Postgres database.

This is a continuation of the web application built in [this repo](https://github.com/westonludeke/todolist_175). Instead of using browser sessions to track user data/user state as in the previous version of the app, a Postgres database is used.

This was built during [Launch School's](https://launchschool.com) RB185 course "Database Applications".

### Project Overview:

This is a Sinatra based To-Do app that allows users to create multiple lists, where each list can contain multiple to-do items, all through the web browser. Both individual to-do items and lists can be created, renamed and deleted, with some validation built in (i.e. preventing duplicate lists, duplicate to-do items on the same list, empty names).

### How to Run the App:

The app can be viewed via Heroku here: https://agile-woodland-57133.herokuapp.com


### Implementation Details:

The goal of this project was to take our small web application that was previously storing user data via cookies using Sinatra's `session` hash and modify it to use a PostgresSQL database instead.

This version of the project is using a separate class, `DatabasePersistence`, to accomplish the connection to a Postgres database and the storage of user data.


