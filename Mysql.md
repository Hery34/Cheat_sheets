# MySQL Cheat Sheet


## Commands
Command | Description
---|---
CREATE DATABASE my_database	| Creates a new database.
USE my_database	| Switches to the specified database.
CREATE TABLE my_table (column1 type, column2 type, ...) | Creates a new table.
INSERT INTO my_table (column1, column2, ...) VALUES (value1, value2, ...) | Inserts a row into a table.
SELECT * FROM my_table	| Selects all rows from a table.
UPDATE my_table SET column1 = value1, column2 = value2 WHERE condition	| Updates a row in a table.
DELETE FROM my_table WHERE condition | Deletes a row from a table.
DROP TABLE my_table	| Deletes a table.
## Tips
You can use the up and down arrow keys to scroll through your command history.
You can use the Tab key to auto-complete filenames and commands.
You can use the following keyboard shortcuts:
Ctrl+C: Cancels the current command.
Ctrl+D: Exits the MySQL client.
Ctrl+Z: Suspends the current command.
You can use the following shell variables:
MYSQL_DATABASE: The name of the default database.
MYSQL_USER: The username for the MySQL client.
MYSQL_PASSWORD: The password for the MySQL client.