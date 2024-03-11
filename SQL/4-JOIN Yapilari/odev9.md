# Ödev 9

1. city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```
SELECT city.city, country.country FROM city INNER JOIN country ON city.country_id = country country_id;
```
2. customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```
SELECT title FROM film WHERE title LIKE '%n' ORDER BY length OFFSET 5 LIMIT 5;
```
3. customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```
SELECT * FROM customer WHERE store_id = 1 ORDER BY last_name DESC LIMIT 4;
```