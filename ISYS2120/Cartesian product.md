  `SELECT S1.studentId AS Id1, S2.studentId AS Id2
    `FROM Student S1, Student S2

This yields a cartesian product between S1 and S2

CROSS JOIN explicitly create a cartesian product