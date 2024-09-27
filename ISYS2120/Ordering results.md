We can specify the required result order in SQL with the ORDER BY clause

SELECT *
  FROM Student
 ORDER BY studentId;

- ORDER BY can only be used at the end of your query
- DESC for descending, ASC for ascending

- ASC as default

SELECT studentId, age, address
  FROM Student
 ORDER BY age DESC, address ASC;

Allows for multi-attribute, age first then address