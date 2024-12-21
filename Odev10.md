`Soru 1:`city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.
```SQL
Select city.city,country.country From city
Left join country on country.country_id = city.country_id
```
`Soru 2:`customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.
```SQL
Select p.payment_id,c.first_name,c.last_name From customer c
Right Join payment p on p.customer_id = c.customer_id
```
`Soru 3:`customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.
```SQL
Select r.rental_id,c.first_name,c.last_name From customer c
Full Join rental r on r.customer_id = c.customer_id
```
