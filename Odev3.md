### Merhabalar,Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.
`Soru 1:`country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.
```SQL
Select * From country Where country like 'A%a';
```
`Soru 2:`country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.
```SQL
Select * From country Where country like '%_____n';
```
`Soru 3:`film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.
```SQL
Select * From film Where title ilike '%T%T%T%T';
```
`Soru 4:`film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.
```SQL
Select * From film Where title like 'T%' and length>90 and rental_rate=2.99;
```
