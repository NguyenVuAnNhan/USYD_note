IS NULL/IS NOT NULL
- Used to check whether a given expression is or is not NULL

'' is not NULL and 0 is not NULL

= operator yields NULL when comparing with NULL

\pset null '[NULL]'
SELECT * FROM Enrolled;

PostgreSQL code to make NULL visible

SELECT studentId, COALESCE(grade, '[UNKNOWN]')
  FROM Enrolled;

COALESCE() replace all NULL with a meaningful value during query evaluation