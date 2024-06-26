SELECT AVG(rental_rate) FROM film;

SELECT COUNT(title) FROM film
WHERE title LIKE 'C%';

SELECT MAX(lenght) FROM film
WHERE rental_rate = 0.99;

SELECT COUNT(DISTINCT(replacement_cost)) FROM film
WHERE lenght > 150;