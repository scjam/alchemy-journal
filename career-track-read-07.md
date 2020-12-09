## 12-08-2020

### PostgreSQL Joins
- You can join tables in SQL based on the values of common columns
- inner join , if values are equal, the inner join creates a new row
- left or right join, versions of the same thing
- full outer join, without a match the column's value will be null

### One-to-one
- https://www.youtube.com/watch?v=PTtlbDkE_BI
- One row in a table may be linked with only one row in another table
- A relationship

### One-to-many
- One row in a table may be linked to many rows in another table

### Many-to-many
- A book can be written by several authors, and an author can write several books
- Must use a join table with the ids to match the information
