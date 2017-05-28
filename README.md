# exercise-3-sql

Write a procedure in MySQL to split a column into rows using a delimiter.

CREATE TABLE sometbl ( ID INT, NAME VARCHAR(50) );

INSERT INTO sometbl VALUES (1, 'Smith'), (2, 'Julio|Jones|Falcons'), (3,

'White|Snow'), (4, 'Paint|It|Red'), (5, 'Green|Lantern'), (6, 'Brown|bag');

For (2), example rows would look like >> “3, white”, “3, Snow” ...
