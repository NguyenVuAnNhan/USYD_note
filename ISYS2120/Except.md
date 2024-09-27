  `SELECT studentId
    `FROM Enrolled
   `WHERE uosCode = 'INFO2120'
    `     AND grade IS NOT NULL
`EXCEPT
  `SELECT studentId
    `FROM Enrolled
   `WHERE uosCode = 'INFO3005'

The EXCEPT operator removes all tuples from the first result set that also exist in the second set 