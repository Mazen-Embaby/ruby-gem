# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

  - Check the config folder -> database.yml to install postgre
  - Check connection parameter in database.yml

* Database creation

  create an empty database for you

   `$ rake db:create`

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...



project structure

| File/Folder | Purpose                                                      |
| :---------- | :----------------------------------------------------------- |
| README      | This is a brief instruction manual for your application. Use it to tell others what your application does, how to set it up, and so on. |
| Rakefile    | This file contains batch jobs that can be run from the terminal. |
| app/        | Contains the controllers, models, and views for your application. You’ll focus on this folder for the remainder of this guide. |
| config/     | Configure your application’s runtime rules, routes, database, and more. |
| db/         | Shows your current database schema, as well as the database migrations. You’ll learn about migrations shortly. |
| doc/        | In-depth documentation for your application.                 |
| lib/        | Extended modules for your application (not covered in this guide). |
| log/        | Application log files.                                       |
| public/     | The only folder seen to the world as-is. This is where your images, javascript, stylesheets (CSS), and other static files go. |
| script/     | Scripts provided by Rails to do recurring tasks, such as benchmarking, plugin installation, and starting the console or the web server. |
| test/       | Unit tests, fixtures, and other test apparatus. These are covered in [Testing Rails Applications](https://guides.rubyonrails.org/v2.3/testing.html) |
| tmp/        | Temporary files                                              |
| vendor/     | A place for third-party code. In a typical Rails application, this includes Ruby Gems, the Rails source code (if you install it into your project) and plugins containing additional prepackaged functionality. |
