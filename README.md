# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
2.7.1

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Example rails commands
```
yarn -v
rails --version
rails routes
rails server
rails db:migrate
rails generate controller Welcome index
rails generate controller Articles
rails generate controller Comments
rails generate model Article title:string text:text
rails generate model Comment commenter:string body:text article:references
```