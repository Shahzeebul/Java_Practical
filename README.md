# java_practical

CREATE DATABASE example_db;
use example_db;

CREATE TABLE register (
    name VARCHAR(50),
    email VARCHAR(50),
    password VARCHAR(50),
    gender VARCHAR(50),
    city VARCHAR(50)
);

DESC register;

select * from register;
