-- Select all students---
SELECT * FROM students;

-- Find the highest score---
SELECT MAX(score) AS highest_score FROM students;

-- Find the lowest score---
SELECT MIN(score) AS lowest_score FROM students;

-- Count how many students---
SELECT COUNT(*) AS total_students FROM students;

-- Find students with name starting with 'A'---
SELECT * FROM students WHERE name LIKE 'A%';
