# Migrations:
- python manage.py makemigrations
it will be generate like git files of changes applied in our project 
 + each migration describe set of changes

## For generate database schema
- python manage.py migrate
<!-- you can open link in terminal to see sqllite -->

## SQLite database:
+ install sqlite extension
+ see - command paletter search sqlite database open it up and it will be file explorer botto section 
+ inspect the migration table
### See actual SQL code:
Sql code send at runtime 
- python manage.py sqlmigrate name-of-app migration-sequence(0003) 
