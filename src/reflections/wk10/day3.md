Journal 42

In a SQL table, what is the difference between information in a row and information in a column?

A column is the index attribute given to the data wheras the row is the entire section given to one instance of a table element.

Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE characters(
  id int NOT NULL,
  description VARCHAR(255) NOT NULL,
  name string,
  age int,
  description strings,
);

What is the difference between the following statements:

DELETE FROM table_name;
DROP TABLE table_name;

Delete from would delete a specific index property and drop would delete the entire table.

Made database changes to gregslist instead of doing knights
https://github.com/AlexMuir138/Gregslist.git