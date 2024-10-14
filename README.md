# README

Ruby version - 2.7.0
Rails version - 6.1.7.3

How to run the project:
* git clone git@github.com:vasylchik/vinyl_pro.git

* cd vinyl_pro

* run psql

* create a new DB user, db & grand all the needed rights
  * CREATE USER my_new_user WITH PASSWORD 'my_password';
  * CREATE DATABASE vinyl_pro_development;
  * GRANT ALL PRIVILEGES ON DATABASE my_database TO my_new_user; # only for local development

* cp .env-template .env

* Replace the value of DATABASE_USERNAME & DATABASE_PASSWORD to the one you used to configure the DB.

* bundle install

* rails s
