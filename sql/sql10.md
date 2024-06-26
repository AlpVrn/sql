SELECT city, country FROM city
LEFT JOIN country ON city.city_id = country.country_id;

SELECT payment_id, first_name, last_name FROM payment
RIGHT JOIN customer ON payment.payment_id = customer.customer_id;

SELECT rental_id, first_name, last_name FROM rental
FULL JOIN customer ON rental.rental_id = customer.customer_id;