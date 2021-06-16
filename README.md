# Tutorial Instalation

Please follow my instructions:

Step 1 - Clone Project

git clone this repo

Step 2 - Create Database

Please create a database named api_backend_test

Step 3 - Config Environment

Rename the .env.example file to .env

Step 4 - Migrate Table Users

Follow this command through the terminal:

php spark migrate

Step 5 - Testing

Follow this command through the terminal:

php spark serve

Then open the postman software with the post method.

Register URL:

localhost:8080/auth/register

Body Params:
first_name, last_name, email, password

Login:

localhost:8080/auth/login

Body Params:
email, password
