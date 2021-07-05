#นี่คือโปรเจคหลักของพวกมึงนะพวกเหี้ย

#How to install project

* clone project

* go to directory to project

#confic Database
* sudo -u postgres psql

* CREATE ROLE csmjuproject WITH SUPERUSER CREATEDB CREATEROLE LOGIN ENCRYPTED PASSWORD 'csmjuproject';

* CREATE DATABASE "main_project_development";

* GRANT ALL PRIVILEGES ON DATABASE "main_project_development" TO csmjuproject;

* GRANT CONNECT ON DATABASE "main_project_development" TO csmjuproject;

* config/database.yml in development and test insert username: csmjuproject , password: csmjuproject

* rails db:create

* rails db:migrate

* rails s# End
