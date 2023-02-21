# demo
demo project using SpringBoot, MySQL, Hibernate and Angular

# step 1
create the MySQL database using the following commands:

```
create database db_example;                   -- Creates the new database

create user 'springuser'@'%' identified by '123456';        -- Creates the user

grant all on db_example.* to 'springuser'@'%';            -- Gives all privileges to the new user on the newly created database
```

# step 2
start spring boot application on port 8080

# step 3
start the angular application on port 4200
