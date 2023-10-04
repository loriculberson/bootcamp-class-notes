## SQL Installation:

- https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide
- **NOTE:** You will need to set a password for MySQL. Please make the password “Password1”. This is not a time to be creative.

`mysql -u root -p`

- https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide
- NOTE: You will need to set a password for MySQL. Please make the password “Password1”. This is not a time to be creative.

## SQL Commands Cheatsheet/Data Types:

- https://gist.github.com/bradtraversy/c831baaad44343cc945e76c2e30927b3
- https://janikvonrotz.ch/2015/07/02/sql-cheat-sheet/
- https://dev.mysql.com/doc/refman/8.0/en/data-types.html

## Big Employee Database

1. `mkdir sql` in your playground
2. cd into sql
3. clone this repo: https://github.com/datacharmer/test_db
4. cd into test_db
5. `mysql -u root -p`  then enter your password
6. type: `source employees.sql`


Next...
- `show databases;`
- `use employees;`
- `show tables;`
- `describe employees;`  (this is the employees table, not the db)

Query

`SELECT first_name, last_name, birth_date FROM employees WHERE MONTH(birth_date) = 3 Limit 25;`
