  `SELECT studentId
    `FROM Enrolled
   `WHERE uosCode = 'INFO2120'
`INTERSECT
  `SELECT studentId
    `FROM Enrolled
   `WHERE uosCode = 'INFO3005'

INTERSECT combines the results of two queries by determining their set intersection