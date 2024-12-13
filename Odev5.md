`Soru 1:`film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en uzun (length) 5 filmi sıralayınız.
```SQL 
Select * From film
Where title like '%n'
Order By length Desc
Limit 5;
```
`Soru 2:`film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en kısa (length) ikinci(6,7,8,9,10) 5 filmi(6,7,8,9,10) sıralayınız.
```SQL
Select * From film
Where title like '%n'
Order By length
Offset 5
Limit 5;
```
`Soru 3:`customer tablosunda bulunan last_name sütununa göre azalan yapılan sıralamada store_id 1 olmak koşuluyla ilk 4 veriyi sıralayınız.
```SQL
Select * From customer 
Where store_id = 1
Order By last_name desc
Limit 4;
```
