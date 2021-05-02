This script simulates the registration method in a webpage. It is composed of a registration process, a verification process and an information storage process using HTML and Java. It is recommended to open the projects as Eclipse IDE projects.

The pipeline is the following:

- First, Execute registro.html --> Here, you will be asked to provide a username and a password
- A connection with a database will be created. If the username and password is in the database, the system will display that the user already exists.
- Otherwise, the user will be asked to introduce further data (email, mail code...).
- When introducing it, the user will have the option to modify the data or to confirm the introduced data.
- If confirmed, the data will be stored in the database.

Before executing the script, the following commands must be executed on MySQL in order to set up the database and the tables within it:

CREATE DATABASE LISTA_NOMBRES;
USE LISTA_NOMBRES;
CREATE TABLE LISTA(NAME TEXT(50), APELLIDO TEXT(50), CONTRASEÑA TEXT(50), EMAIL TEXT(50), POSTAL TEXT(50));

+ Make sure that the IP of the server is the changed to the apropriate one, as well as the username and the password of your MySQL

