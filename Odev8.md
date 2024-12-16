`Soru 1: `test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```SQL
Create table employee
(
id integer,
name varchar(50),
email varchar(100),
birthday date
)
```
`Soru 2: `Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```SQL
insert into employee (Id, FullName, Email, Birthday) values (1, 'Evanne Lashley', 'elashley0@addthis.com', '1996-12-08');
insert into employee (Id, FullName, Email, Birthday) values (2, 'Anatola Gallear', 'agallear1@aol.com', '1994-07-12');
insert into employee (Id, FullName, Email, Birthday) values (3, 'Shurlock Danford', 'sdanford2@china.com.cn', '1987-07-28');
insert into employee (Id, FullName, Email, Birthday) values (4, 'Mercie Burchatt', 'mburchatt3@github.io', '1982-02-09');
insert into employee (Id, FullName, Email, Birthday) values (5, 'Pernell Sebley', 'psebley4@elegantthemes.com', '1973-05-29');
insert into employee (Id, FullName, Email, Birthday) values (6, 'Konstantine Alton', 'kalton5@ning.com', '1976-08-28');
insert into employee (Id, FullName, Email, Birthday) values (7, 'Laraine Pablos', 'lpablos6@youtube.com', '1982-07-13');
insert into employee (Id, FullName, Email, Birthday) values (8, 'Aldin Ketteman', 'aketteman7@ed.gov', '1999-05-13');
insert into employee (Id, FullName, Email, Birthday) values (9, 'Lotte Duggon', 'lduggon8@a8.net', '1986-11-29');
insert into employee (Id, FullName, Email, Birthday) values (10, 'Liana Marzelo', 'lmarzelo9@skype.com', '1996-12-10');
insert into employee (Id, FullName, Email, Birthday) values (11, 'Eveline O''Cahill', 'eocahilla@umich.edu', '2000-10-24');
insert into employee (Id, FullName, Email, Birthday) values (12, 'Iseabal Fackney', 'ifackneyb@de.vu', '1982-07-13');
insert into employee (Id, FullName, Email, Birthday) values (13, 'Duffie Ault', 'daultc@china.com.cn', '1987-02-13');
insert into employee (Id, FullName, Email, Birthday) values (14, 'Renato Fenkel', 'rfenkeld@mozilla.com', '1992-11-05');
insert into employee (Id, FullName, Email, Birthday) values (15, 'Sumner Millican', 'smillicane@noaa.gov', '1981-01-03');
insert into employee (Id, FullName, Email, Birthday) values (16, 'Leese Vasyukov', 'lvasyukovf@seesaa.net', '1975-02-27');
insert into employee (Id, FullName, Email, Birthday) values (17, 'Davita Louca', 'dloucag@sourceforge.net', '1975-06-04');
insert into employee (Id, FullName, Email, Birthday) values (18, 'Isaac Blowing', 'iblowingh@flickr.com', '1973-08-09');
insert into employee (Id, FullName, Email, Birthday) values (19, 'Alphard Dursley', 'adursleyi@twitpic.com', '1981-05-18');
insert into employee (Id, FullName, Email, Birthday) values (20, 'Ula Tackle', 'utacklej@craigslist.org', '1973-02-26');
insert into employee (Id, FullName, Email, Birthday) values (21, 'Jule Sowrah', 'jsowrahk@sina.com.cn', '1973-05-20');
insert into employee (Id, FullName, Email, Birthday) values (22, 'Dehlia Blenkinsop', 'dblenkinsopl@youku.com', '1996-09-06');
insert into employee (Id, FullName, Email, Birthday) values (23, 'Halley Rawlings', 'hrawlingsm@scientificamerican.com', '1974-02-28');
insert into employee (Id, FullName, Email, Birthday) values (24, 'Dar Stopps', 'dstoppsn@cocolog-nifty.com', '1974-10-26');
insert into employee (Id, FullName, Email, Birthday) values (25, 'Hashim Kubelka', 'hkubelkao@constantcontact.com', '1974-02-21');
insert into employee (Id, FullName, Email, Birthday) values (26, 'Frayda Nicolson', 'fnicolsonp@tmall.com', '1996-04-30');
insert into employee (Id, FullName, Email, Birthday) values (27, 'Calv McGirr', 'cmcgirrq@slideshare.net', '1985-02-23');
insert into employee (Id, FullName, Email, Birthday) values (28, 'Job Niave', 'jniaver@squarespace.com', '2000-01-28');
insert into employee (Id, FullName, Email, Birthday) values (29, 'Arch Gethin', 'agethins@nih.gov', '1985-02-26');
insert into employee (Id, FullName, Email, Birthday) values (30, 'Honey Epp', 'heppt@ustream.tv', '1993-10-11');
insert into employee (Id, FullName, Email, Birthday) values (31, 'Mile Frangleton', 'mfrangletonu@lulu.com', '1998-10-17');
insert into employee (Id, FullName, Email, Birthday) values (32, 'Eachelle Fairholm', 'efairholmv@spiegel.de', '1999-10-10');
insert into employee (Id, FullName, Email, Birthday) values (33, 'Tiffy Halston', 'thalstonw@imageshack.us', '1997-08-14');
insert into employee (Id, FullName, Email, Birthday) values (34, 'Collie Diano', 'cdianox@ow.ly', '1976-09-16');
insert into employee (Id, FullName, Email, Birthday) values (35, 'Karilynn McGettrick', 'kmcgettricky@de.vu', '1975-03-20');
insert into employee (Id, FullName, Email, Birthday) values (36, 'Jermaine Shreve', 'jshrevez@auda.org.au', '1975-08-31');
insert into employee (Id, FullName, Email, Birthday) values (37, 'Francesca Gierardi', 'fgierardi10@sourceforge.net', '1997-02-07');
insert into employee (Id, FullName, Email, Birthday) values (38, 'Romy Altimas', 'raltimas11@discovery.com', '1977-02-06');
insert into employee (Id, FullName, Email, Birthday) values (39, 'Evelyn Lintill', 'elintill12@macromedia.com', '1985-12-26');
insert into employee (Id, FullName, Email, Birthday) values (40, 'Morten Creeghan', 'mcreeghan13@e-recht24.de', '1981-10-24');
insert into employee (Id, FullName, Email, Birthday) values (41, 'Noellyn Milksop', 'nmilksop14@japanpost.jp', '1985-11-04');
insert into employee (Id, FullName, Email, Birthday) values (42, 'Carline Philbin', 'cphilbin15@github.com', '1983-11-08');
insert into employee (Id, FullName, Email, Birthday) values (43, 'Agata Merle', 'amerle16@free.fr', '1981-01-17');
insert into employee (Id, FullName, Email, Birthday) values (44, 'Dylan Pettegre', 'dpettegre17@mlb.com', '1979-11-18');
insert into employee (Id, FullName, Email, Birthday) values (45, 'Sella Babinski', 'sbabinski18@pagesperso-orange.fr', '1994-06-26');
insert into employee (Id, FullName, Email, Birthday) values (46, 'Bernhard Letchmore', 'bletchmore19@uol.com.br', '1972-04-23');
insert into employee (Id, FullName, Email, Birthday) values (47, 'Phillipp Boykett', 'pboykett1a@bbc.co.uk', '1981-06-25');
insert into employee (Id, FullName, Email, Birthday) values (48, 'Reta Ayrton', 'rayrton1b@bbc.co.uk', '1973-06-13');
insert into employee (Id, FullName, Email, Birthday) values (49, 'Kimbell Folder', 'kfolder1c@hostgator.com', '1985-08-29');
insert into employee (Id, FullName, Email, Birthday) values (50, 'Bordie Zuker', 'bzuker1d@dion.ne.jp', '1987-09-23');
```
`Soru 3: `Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```SQL
Update employee
Set
	FullName = 'Ludovico Einaudi'
Where Id = 1
Returning *;

Update employee
Set
	Birthday = '1969-09-14'
Where Id = 1
Returning *;

Update employee
Set
	Email = 'leinaudi@go.com'
Where Id = 1
Returning *;
	
Update employee
Set 
	FullName = 'Tony Anderson'
Where Id = 2
Returning *;

Update employee
Set
	Email = 'tanderson@go.com'
Where Id = 2
Returning *;
```
`Soru 4: `Sütunların her birine göre ilgili satırı silecek 3 adet DELETE işlemi yapalım.
```SQL
Delete From employee
Where Email = 'leinaudi@go.com';

Delete From employee
Where FullName = 'Tony Anderson';

Delete From employee
Where Birthday = '1987-07-28';
```
