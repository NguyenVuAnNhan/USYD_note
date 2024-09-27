SELECT uosCode, uosName
  FROM UnitOfStudy
 WHERE uosName LIKE 'Database%';

This matches with any uosName that starts with "Database", case sensitive

NOT LIKE can be used for anti-matching

% are placeholders representing any sequence of zero or more characters

_ matches exactly one character

LOWER() converts any string value to lowercase

SELECT uosCode, uosName
  FROM UnitOfStudy
 WHERE uosName SIMILAR TO '(Advanced|Data)%';

SELECT uosCode, uosName
  FROM UnitOfStudy
 WHERE uosCode SIMILAR TO 'COMP\[\[:digit:]]{4}';

SIMILAR TO is an updated LIKE

| is or

\[\[:digit:]]{4} for 4 digits

