`Sour 1:`film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?
```SQL
Select Round(Avg(rental_rate),2) From film
```
`Sour 2:`film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?
```SQL
Select Count(title) From film Where title like 'C%';
```
`Sour 3:`film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?
```SQL
Select Max(length) as film_dakikasi From film Where rental_rate = 0.99;
```
`Sour 4:`film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?
```SQL
Select Distinct(replacement_cost) From film Where length>150;
```
