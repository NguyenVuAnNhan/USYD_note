`LIMIT` clause restrict the size of the output to a predefined number of tuples. This would come at the end of a SFW-query.

`SELECT <expression>
  `FROM <tables>
 `WHERE <condition>
 `ORDER BY <sort_expression>
`` LIMIT <positive_integer>

### Top-N queries
We can use `ORDER BY` and `LIMIT` but this will not display ranks

We can use the new `RANK()` function to produce ranks.

`SELECT sid, name, rank() OVER (ORDER BY mark DESC)
  `FROM Student
    ``   NATURAL JOIN Enrolled
 `WHERE uos_code = 'INFO1903'
 `LIMIT 3;
