# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

users
  name: :string
  email: :text
  groups_id: :integer
  password: :text

groups
  name: :text

user_goup
  user_id: :integer
  group_id: :integer

messages
  text: :text
  image: :text
  user_id: :integer


* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
