`Soru 1:`city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```SQL
Select city,country From city
Inner Join country on city.country_id = country.country_id
```
`Soru 2:`customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```SQL
Select distinct c.first_name,c.last_name From customer c
Inner Join payment p on c.customer_id = p.customer_id
Order By 1
```
`Soru 3:`customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```SQL
Select first_name,last_name From customer c
Inner Join rental r on c.customer_id = r.customer_id
```
