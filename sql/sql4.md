SELECT DISTINCT replacement_cost FROM film;

SELECT COUNT(DISTINCT replacement_cost) FROM film;

SELECT DISTINCT COUNT(*) FROM film
WHERE title LIKE 'T%' AND rating ='G';

SELECT DISTINCT COUNT(*) FROM country
WHERE length(country)=5;

SELECT DISTINCT COUNT(*) FROM city
WHERE city ILIKE '%r';