SELECT title ,description FROM film;

SELECT * FROM film
WHERE 75>length and length>60;

SELECT * FROM film 
WHERE rental_rate = 0.99 
and
(replacement_cost = 12.99 or replacement_cost = 28.99);

SELECT last_name FROM customer
WHERE first_name = 'Mary';

SELECT * FROM film
WHERE NOT length > 50 
and
NOT (rental_rate = 2.99 OR rental_rate = 4.99);
