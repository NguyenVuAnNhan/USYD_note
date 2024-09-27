We can use `GROUP BY` to group results for aggregate functions

`SELECT uosCode, COUNT(studentId) AS enrolments
  `FROM Enrolled
 `WHERE year >= 2006
 `GROUP BY uosCode;

We can only list two types of column in the result of a `GROUP BY` query:
- Table attributes by which the group is defined
- Aggregate values computed from the same group

`SELECT uosCode, year, COUNT(studentId) 
  `FROM Enrolled
 `WHERE year >= 2006
 `GROUP BY uosCode, year;

### HAVING
Help us specify a filtering condition for each group

  `SELECT <result_list>
    `FROM <relation(s)>
   `WHERE <per_tuple_condition>
`GROUP BY <list_of_attributes>
 `` HAVING <per_group_condition>

`WHERE` filters the individual tuples **before** they are grouped via `GROUP BY`

`HAVING` filter the whole groups **after** they have been formed by `GROUP BY`