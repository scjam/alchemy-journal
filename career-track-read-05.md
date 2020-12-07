## 12-06-20

### Inside a Computer
- RAM is short term storage, hard drive is long term
- CPU is the brain, silicon chip, size of a thumbnail
- gigahertz is billions of instructions per second
- Unplug your computer before poking around in it

### Postgres Insert
```
INSERT INTO table_name(column1, column2, …)
VALUES (value1, value2, …);
```
- oid = object identifier
- * means all
- You can return the row and rename at the same time
- Need an additional single quote to escape single quotes in a character string

### Postgres Select
- Use select to query data from a table
- SQL keywords are case-insensitive but caps is used to make queries easier to read
- Can merge column info with Select and || ' ' ||

### Postgres Update
- UPDATE lets you change info in existing tables
- Has an optional RETURNING clause that returns the updated rows
- When updating a row(s), using RETURNING *; will just return the updated row(s) instead of all actual rows

### Postgres Delete
- Use DELETE to delete 1+ rows from table
- Delete only removes data, you must use ALTER TABLE to actually change the structure of the table
