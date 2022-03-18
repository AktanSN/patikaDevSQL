# 1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

````SQL
CREATE TABLE employee(
    id INTEGER,
    name VARCHAR(50),
    birthday DATE,
    email VARCHAR(100)
);
````


# 2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

````SQL
insert into employee (id, name, birthday, email) values (1, 'Modesta', '2021-12-11', 'mskitral0@pinterest.com');
insert into employee (id, name, birthday, email) values (2, 'Lila', '2021-12-26', 'lproswell1@blog.com');
insert into employee (id, name, birthday, email) values (3, 'Arlen', '2021-06-05', 'aeriksson2@adobe.com');
insert into employee (id, name, birthday, email) values (4, 'Stu', '2021-09-01', 'sbremner3@uol.com.br');
insert into employee (id, name, birthday, email) values (5, 'Carver', '2021-07-04', 'cpottery4@so-net.ne.jp');
insert into employee (id, name, birthday, email) values (6, 'Dorelia', '2021-07-10', 'dfigure5@blogger.com');
insert into employee (id, name, birthday, email) values (7, 'Darb', '2022-02-14', 'dallerton6@github.io');
insert into employee (id, name, birthday, email) values (8, 'Matty', '2021-05-29', 'mkennion7@netvibes.com');
insert into employee (id, name, birthday, email) values (9, 'Kai', '2021-09-03', 'kpetroff8@yahoo.com');
insert into employee (id, name, birthday, email) values (10, 'Kaylil', '2022-02-16', 'kweedenburg9@wordpress.org');
insert into employee (id, name, birthday, email) values (11, 'Syd', '2021-10-15', 'sfilipputtia@angelfire.com');
insert into employee (id, name, birthday, email) values (12, 'Skelly', '2022-02-19', 'smelendezb@fema.gov');
insert into employee (id, name, birthday, email) values (13, 'Gwendolyn', '2021-04-15', 'gczajkowskac@google.com.hk');
insert into employee (id, name, birthday, email) values (14, 'Andria', '2021-08-09', 'aseeksd@army.mil');
insert into employee (id, name, birthday, email) values (15, 'Ashlee', '2022-03-07', 'agirardettie@craigslist.org');
insert into employee (id, name, birthday, email) values (16, 'Abel', '2021-03-21', 'aocridiganf@vkontakte.ru');
insert into employee (id, name, birthday, email) values (17, 'Amata', '2021-05-30', 'atrundlerg@guardian.co.uk');
insert into employee (id, name, birthday, email) values (18, 'Ethelind', '2021-07-01', 'espoerlh@google.co.jp');
insert into employee (id, name, birthday, email) values (19, 'Louella', '2021-10-14', 'ltewi@newyorker.com');
insert into employee (id, name, birthday, email) values (20, 'Yardley', '2021-10-29', 'ywashingtonj@indiegogo.com');
insert into employee (id, name, birthday, email) values (21, 'Cleveland', '2021-07-23', 'cwhaphamk@hostgator.com');
insert into employee (id, name, birthday, email) values (22, 'Carlee', '2021-10-31', 'cbrotheridgel@eepurl.com');
insert into employee (id, name, birthday, email) values (23, 'Clair', '2021-09-16', 'costridgem@mac.com');
insert into employee (id, name, birthday, email) values (24, 'Leeann', '2021-10-17', 'lgreern@creativecommons.org');
insert into employee (id, name, birthday, email) values (25, 'Garvin', '2022-02-19', 'gdepinnao@cnbc.com');
insert into employee (id, name, birthday, email) values (26, 'Arvie', '2021-11-30', 'aogelbep@yelp.com');
insert into employee (id, name, birthday, email) values (27, 'Gawain', '2021-11-01', 'gabrahamsohnq@mail.ru');
insert into employee (id, name, birthday, email) values (28, 'Giustina', '2021-10-12', 'goleksiakr@disqus.com');
insert into employee (id, name, birthday, email) values (29, 'Debbi', '2022-02-17', 'dleybans@globo.com');
insert into employee (id, name, birthday, email) values (30, 'Evelyn', '2022-01-08', 'erext@soundcloud.com');
insert into employee (id, name, birthday, email) values (31, 'Lexis', '2021-07-28', 'lparnhamu@elpais.com');
insert into employee (id, name, birthday, email) values (32, 'Alon', '2021-05-07', 'agoodreidv@bbb.org');
insert into employee (id, name, birthday, email) values (33, 'Oralle', '2021-03-27', 'ohuychew@opensource.org');
insert into employee (id, name, birthday, email) values (34, 'Elaina', '2021-08-14', 'egotthardsfx@biblegateway.com');
insert into employee (id, name, birthday, email) values (35, 'Kailey', '2022-02-18', 'kdionisoy@ftc.gov');
insert into employee (id, name, birthday, email) values (36, 'Aguie', '2021-10-20', 'agolbournz@trellian.com');
insert into employee (id, name, birthday, email) values (37, 'Valentine', '2022-01-20', 'vsodo10@yale.edu');
insert into employee (id, name, birthday, email) values (38, 'Sile', '2022-01-17', 'sbalogun11@bizjournals.com');
insert into employee (id, name, birthday, email) values (39, 'Winnie', '2021-04-14', 'wcopnall12@sohu.com');
insert into employee (id, name, birthday, email) values (40, 'Marcelle', '2021-07-12', 'msleath13@eepurl.com');
insert into employee (id, name, birthday, email) values (41, 'Stearne', '2021-12-30', 'scrate14@netvibes.com');
insert into employee (id, name, birthday, email) values (42, 'Lavena', '2021-06-30', 'lpullen15@ezinearticles.com');
insert into employee (id, name, birthday, email) values (43, 'Cybill', '2022-02-13', 'cwhopples16@upenn.edu');
insert into employee (id, name, birthday, email) values (44, 'Micaela', '2021-04-22', 'mkilgallen17@stanford.edu');
insert into employee (id, name, birthday, email) values (45, 'Selby', '2022-03-09', 'smainds18@wikipedia.org');
insert into employee (id, name, birthday, email) values (46, 'Bryana', '2021-04-07', 'bsherbrook19@list-manage.com');
insert into employee (id, name, birthday, email) values (47, 'Jaime', '2021-05-05', 'jmasarrat1a@si.edu');
insert into employee (id, name, birthday, email) values (48, 'Desmond', '2021-08-16', 'dbanger1b@bloglovin.com');
insert into employee (id, name, birthday, email) values (49, 'Jacquette', '2021-09-12', 'jfulger1c@dion.ne.jp');
insert into employee (id, name, birthday, email) values (50, 'Eustace', '2022-01-02', 'ehollyar1d@xrea.com');
````

# 3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

````SQL
UPDATE employee SET birthday = '2022-03-18',
name = 'DegisenIsim',
email = 'Degisti@gmail.com'
WHERE id = 50;

UPDATE employee SET birthday = '2022-03-18',
name = 'DegisenIsim',
email = 'Degisti@gmail.com'
WHERE id = 49;

UPDATE employee SET birthday = '2022-03-18',
name = 'DegisenIsim',
email = 'Degisti@gmail.com'
WHERE id = 48;

UPDATE employee SET birthday = '2022-03-18',
name = 'DegisenIsim',
email = 'Degisti@gmail.com'
WHERE id = 47;

UPDATE employee SET birthday = '2022-03-18',
name = 'DegisenIsim',
email = 'Degisti@gmail.com'
WHERE id = 46;
````

# 4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

````SQL
DELETE FROM employee WHERE id = 50;

DELETE FROM employee WHERE id = 49;

DELETE FROM employee WHERE id = 48;

DELETE FROM employee WHERE id = 47;

DELETE FROM employee WHERE id = 46;
````