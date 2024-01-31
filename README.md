# SQL-Ödev9

1. City tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```
SELECT city.city,country.country
FROM city
INNER JOIN country 
ON city.city_id = country.country_id;
```
2. Customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```
SELECT payment.payment_id,customer.first_name,customer.last_name
FROM payment
INNER JOIN customer
ON payment.staff_id = customer.store_id;
```
3. Customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```
SELECT rental.rental_id, customer.first_name, customer.last_name
FROM rental
INNER JOIN customer
ON rental.rental_id = customer.customer_id;
```
