## SQL Bolt (1-4, 13-18)

https://sqlbolt.com/

<ul>
<li>SQL: Structured Query Language. Allows both technical & non-technical users query,manipulate, and transform data from a relational database.
<li>Relational database: represents a collection of related (2D) tables (eg Excel). 
<li>CAPS aren't needed
<li> are used so we know which words are SQL keywords vs names-- makes query easier to read!
<li>SELECT (queries) - declares what data we are looking for. When selecting multiples of something (e.g., title and director from movies example) you separate them with a comma. SELECT title, director FROM movies;. SELECT * FROM movies to select all info.
<li>WHERE condition:
</ul>
    SELECT col_name1, col_name2, …
    FROM table_name
    WHERE condition
        AND/OR another_condition
        AND/OR …;
<ul>
<li>Can use BETWEEN...AND for greater than x and less than y
<li>All strings must be between quotes in SQL
<li> = // !- // <> - 
<li>LIKE
<li>DISTINCT
<li>GROUP BY
<li>ORDER BY
<li>ASC/DESC
<li>LIMIT / OFFSET
<li>LIMIT
<li>OFFSET
<li>SELECT DISTINCT col_name FROM movies, ORDER BY director ASC; Inserting Rows SQL schemas and how to add new data INSERT INTO tablename to insert followed by VALUES (values here), (more values)
<li>UPDATE tablename to update data SET to set the data WHERE apply the changes 'where' it satisfies the condition
<li>DELETE FROM tablename WHERE condition is this
<li>CREATE TABLE to create table CREATE TABLE IF NOT EXISTS tablename column DataType (INTEGER, TEXT, BOOLEAN, BLOG, DATE,etc.) TableConstraint (ex. PRIMARY KEY, UNIQUE, NOT NULL, etc.) DEFAULT default_value, repeat if there is more
<li>Altering Tables ALTER TABLE statement adds, removes, or modifies columns and table constraints 
<li>ADD to add DROP to delete RENAME TO rename
<li>Dropping Tables DROP IF TABLE EXITS tablename