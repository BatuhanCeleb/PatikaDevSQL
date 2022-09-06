Soru 1
```
SELECT city, country FROM country
LEFT JOIN city
On country.country_id = city.country_id

```

Soru 2
```
SELECT first_name, last_name FROM payment
RIGHT JOIN customer
On payment.customer_id = customer.customer_id

```

Soru 3
```
SELECT rental_id, first_name, last_name FROM rental
FULL JOIN customer
On rental.customer_id = customer.customer_id

```
