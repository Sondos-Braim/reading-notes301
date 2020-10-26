
#Read 8

## SQL

-Databases have a structure that is similar to tables.

-The databases can be used to access the data and to store data and create your own tables.

-When we want to use a certain part of the database we can use the keyword `SELECT` and then specify the part and the name of the table.

-SQL doesn't require you to write the keywords all capitalized, but as a convention, it helps people distinguish SQL keywords from column and tables names, and makes the query easier to read.

-It is not possible to read through all the rows of the columns chosen but you can use the `WHERE` keyword and then using conditional statements to filter the selected data. 

-We can also search for certain words using different sensitive and insensitive keywords.

-you can also order the columns in order to make it easier to reach it when we have a table of thousands or maybe millions of rows

-normalization is the process of organizing data in more than one table and it is better in order for us not to have duplicates in the same table There are ways in which you can select data from more than one table.

-Using the `JOIN` clause in a query, we can combine row data across two separate tables using this unique key. The first of the joins that we will introduce is the `INNER JOIN`.

-If the two tables have asymmetric data, which can easily happen when data is entered in different stages, then we would have to use a `LEFT JOIN`, `RIGHT JOIN` or `FULL JOIN` instead to ensure that the data you need is not left out of the results.

-An alternative to NULL values in your database is to have data-type appropriate default values, like 0 for numerical data, empty strings for text data, etc. But if your database needs to store incomplete data, then NULL values can be appropriate if the default values will skew later analysis (for example, when taking averages of numerical data).

-Sometimes, it's also not possible to avoid NULL values, as we saw in the last lesson when outer-joining two tables with asymmetric data. In these cases, you can test a column for NULL values in a WHERE clause by using either the IS NULL or IS NOT NULL constraint.

Each database has its own supported set of mathematical, string, and date functions that can be used in a query, which you can find in their own respective docs.

-The use of expressions can save time and extra post-processing of the result data, but can also make the query harder to read, so we recommend that when expressions are used in the SELECT part of the query, that they are also given a descriptive alias using the AS keyword.

-Order of execution of a Query:

1. FROM and JOINs

2. WHERE

3. GROUP BY

4. HAVING

5. SELECT

6. DISTINCT

7. ORDER BY

8. LIMIT / OFFSET
