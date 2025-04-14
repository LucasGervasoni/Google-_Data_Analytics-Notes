# SQL guide: Getting started

Structured Query Language (or SQL, often pronounced “sequel”) enables data analysts to talk to their databases. SQL is one of the most useful data analyst tools, especially when working with large datasets in tables.

### What is a query?
A query is a request for data or information from a database. When you query databases, you use SQL to communicate your question or request. You and the database can always exchange information as long as you speak the same language.

Every programming language, including SQL, follows a unique set of guidelines known as syntax. Syntax is the predetermined structure of a language that includes all required words, symbols, and punctuation, as well as their proper placement. As soon as you enter your search criteria using the correct syntax, the query starts working to pull the data you’ve requested from the target database.

The syntax of every SQL query is the same:

- Use `SELECT` to choose the columns you want to return.
- Use `FROM` to choose the tables where the columns you want are located.
- Use `WHERE` to filter for certain information.

```sql
SELECT
FROM
WHERE

SELECT
    Specifies the columns from which to retrieve data
FROM
    Specifies the table from which to retrieve data
WHERE
    Specifies criteria that the data must meet
```

### Example of a query
```sql
SELECT first_name
FROM customer_data.customer_name
WHERE first_name = 'Tony'
```

### Multiple columns in a query
```sql
SELECT
    ColumnA,
    ColumnB,
    ColumnC
FROM
    Table where the data lives
WHERE
    Certain condition is met


SELECT
    customer_id,
    first_name,
    last_name
FROM
    customer_data.customer_name
WHERE
    first_name = 'Tony'
```
