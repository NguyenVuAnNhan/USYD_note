CREATE VIEW

CREATE VIEW CurrentStudents AS
  SELECT studentId, uosCode, semester
    FROM Enrolled
   WHERE year = 2016;
   
SELECT *
  FROM CurrentStudents;

DDL statement extends current database schema with a new view

AS renaming operator can be used to define custom names for the view attributes

DROP VIEW <viewname>;

Delete a view