INSERT INTO <tablename>
	VALUES (...);

When not specified the schema of <tablename>, the values have to be listed in exactly the same order as specified in the database schema

You can explicitly list the attributes as part of the insert statement

INSERT INTO <tablename>(<attribute1>, <attribute2>) 
     VALUES (<value1>, <value2>);

Return the internal id and the number of rows inserted