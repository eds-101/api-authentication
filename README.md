# README

* We want to support the following endpoints: 1. Get a list of existing users (GET /users) 2. Create a user (POST /users) 3. Log in with an existing user email + password (POST /users/login)

* Here’s the process.

* The front-end sends the email and password (POST /users/login)
* We authenticate the email/password and, if successful, create a JSON Web Token and send it back.
* The front-end uses that token on every subsequent request to let us know it’s a valid user.

* This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
