SELECT *
  FROM Student NATURAL JOIN Enrolled
 WHERE uosCode = 'INFO2120';

Join everywhere that has attributes of the same name with the same value

NATURAL JOIN only shows attributes' names once

When there is no common attributes, NATURAL JOIN return the cross product of both tables