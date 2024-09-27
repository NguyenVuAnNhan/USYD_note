CREATE TABLE command extends the current database schema with a new table

CREATE TABLE <tablename> (
  <attr1> <TYPE1>,
  <attr2> <TYPE2>,
  ...
);

Each attribute must have a specific domain type:
SMALLINT - 2 byte numeric integer
INTEGER - 4 byte numeric integer
FLOAT - 8 byte floating point value
CHAR(n) - fixed length string of n characters
VARCHAR(n) - variable length string of 0 to n characters
