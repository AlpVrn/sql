SELECT country FROM country
WHERE country 
ILIKE 'A%a';

SELECT * FROM country
WHERE length(country)>=6 
AND 
country LIKE '%n';

SELECT title FROM film
WHERE title 
LIKE '%t%t%t%t%';

SELECT * FROM film
WHERE title 
LIKE 'C%' AND length>90 
AND 
rental_rate = 2.99;