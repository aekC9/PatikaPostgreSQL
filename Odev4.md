`Soru 1:`film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
```SQL
Select distinct replacement_cost From film;
```
`Soru 2:`film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
```SQL
Select count(distinct replacement_cost) From film;
```
`Soru 3:`film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
```SQL
Select * From film Where title like 'T%' and rating = 'G';
```
`Soru 4:`country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
```SQL
Select Count(*) From country Where country like '_____';
```
`Soru 5:`city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
```SQL
Select Count(*) From city Where city ilike '%R';
```
