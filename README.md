# Instruction

## Create a database for the ToDo App Project
### Download PostgreSQL App
#### For MacOS
Download it from: https://postgresapp.com/
#### For WinOS
Download it from: https://www.postgresql.org/download/windows/

### Make a new database
Here, our db name will be `mydatabase`.
In the database terminal, write the code below.
``` 
use mydatabase
```
`use <db name>`, this command makes a new database or switch to that db.

### Create the table and columns we need
In the database terminal, switch to our db, `mydatabase`, with the command below.
``` 
use mydatabase
``` 
Then, copy all the code from `database.sql` file, and paste it into the database terminal, to create the table and columns we need.

## The `todo` column was called `name` column
If your database already exits, and you want to change the old column name from `name` to `todo`, please switch to our db, `mydatabase`, and run the code below.

```
ALTER TABLE my_table
RENAME COLUMN name TO todo;
```