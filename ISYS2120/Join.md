SELECT Student.studentId, name
  FROM Student, Enrolled
 WHERE Student.studentId = Enrolled.studentId
       AND Enrolled.uosCode = 'INFO2120';

Here, the condition is Student.studentId = Enrolled.studentId, this is an equi-join

Without join condition, a cartesian join will happen

SELECT S.studentId, name
  FROM Student S, Enrolled E, UnitOfStudy U
 WHERE S.studentId = E.studentId
       AND U.uosCode = E.uosCode
       AND U.uosName = 'Database Systems I';

Multiple explicit joins can be done by nicknaming tables