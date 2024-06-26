SELECT title, lenght FROM film
WHERE title LIKE '%n'
ORDER BY lenght DESC
LIMIT 5;

SELECT title, lenght FROM film
WHERE title LIKE '%n'
ORDER BY lenght
OFFSET 5
LIMIT 5;

SELECT * FROM costumer
WHERE store_id = 1
ORDER BY last_name DESC
LIMIT 4;