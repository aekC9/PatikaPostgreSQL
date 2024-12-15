`Soru 1:` film tablosunda bulunan filmleri rating değerlerine göre gruplayınız.
```SQL
Select film_id,title,rating From film
Group By rating,title,film_id
Order By rating 
```
`Soru 2:` film tablosunda bulunan filmleri replacement_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replacement_cost değerini ve karşılık gelen film sayısını sıralayınız.
```SQL
Select replacement_cost,count(title) as film_count From film
Group By replacement_cost
Having Count(title)>50;
```
`Soru 3:` customer tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını nelerdir?
```SQL
Select store_id,Count(store_id) as customer_count From customer
Group By store_id
```
`Soru 4:` city tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.
```SQL
Select country_id,Count(city) city_count From city 
Group By country_id
Order By city_count desc
```
