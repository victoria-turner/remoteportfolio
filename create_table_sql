CREATE TABLE friends(
  id INTEGER,
  name TEXT,
  birthday DATE
);

INSERT INTO friends (id,name,birthday)
VALUES (1,"Ororo","1940-05-30");

INSERT INTO friends (id,name,birthday)
VALUES (2,"Apollo","2002-11-22");

INSERT INTO friends (id,name,birthday)
VALUES (3,"Jess","2003-08-15");

UPDATE friends
SET name = "Storm"
WHERE id = 1;

ALTER TABLE friends
ADD COLUMN email TEXT;

UPDATE friends
SET email = "storm@codecademy.com"
WHERE id = 1;

UPDATE friends
SET email = "apollohollow@gmail.com"
WHERE id = 2;

UPDATE friends
SET email = "jessthebess@gmail.com"
WHERE id = 3;

DELETE FROM friends
WHERE id = 1;

SELECT * 
FROM friends;
