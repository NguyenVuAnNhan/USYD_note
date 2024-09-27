### Co-related subqueries
- Executed for each tuple of the outer query. The search condition refers to at least one attribute of the outer query.

`SELECT studentId, name
  `FROM Student S
 `WHERE EXISTS (SELECT *
   ``              FROM Enrolled E
    ``            WHERE E.studentId = S.studentId
      ``                AND uosCode = 'INFO2120')

### Non-co-related subqueries
- Executed only once, the result used for all tuples of the outer query

`SELECT studentId, name
  `FROM Student
 `WHERE studentId IN (SELECT E.studentId
   ``                    FROM Enrolled E
    ``                  WHERE E.uosCode = 'INFO2120')

Subqueries can be used in the FROM clause. Note that PostgreSQL requires you to give the result of a sub-query in the `FROM` clause a name using the `AS` rename operator. Also the `WHERE` clause.

### EXISTS
We can use `EXISTS` and `NOT EXISTS` to check for existence of a particular query value