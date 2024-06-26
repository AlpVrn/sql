SELECT COUNT(*) FROM film
WHERE lenght >
(
    SELECT AVG(lenght) FROM film;
);


SELECT COUNT(*) FROM film
WHERE rental_rate =
(
    SELECT MAX(lenght) FROM film;
);

SELECT * FROM film
WHERE rental_rate =
(
    SELECT MIN(rental_rate) FROM film;
)
AND replacement_cost =
(
    SELECT MIN(replacement_cost) FROM film;
);

SELECT customer_id, COUNT(*) AS most_purchases FROM payment
GROUP BY customer_id
ORDER BY most_purchases DESC;