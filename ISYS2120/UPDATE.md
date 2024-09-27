Modify the data in one or more rows of the specified table

<tablename> refers to an existing table name in the database schema

<expression> is a comma-separated list of <attr = value> expressions that compute a new value for one or more attributes based on constants and other attribute values. it can be a complex computation or even include sub-queries with select

<condition> refers to a filtering condition, which must be true for such tuples that get updated. Without it, all row in <tablename> will be updated

Return the number of rows updated

UPDATE <tablename>
SET <expression>
WHERE <condition>;



