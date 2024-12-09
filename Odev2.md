## Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.
`Soru 1:`film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız.)
```SQL
Select * From film Where replacement_cost Between 12.99 and  16.99;
```
`Soru 2:`actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız.)
```SQL
Select first_name,last_name From actor Where first_name in ('Penelope','Nick','Ed');
```
`Soru 3:`film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 olma koşullarıyla sıralayınız. ( IN operatörünü kullanınız.)
```SQL
Select * From film Where (rental_rate in (0.99,2.99,4.99)) AND (replacement_cost IN (12.99,15.99,28.99));
```
