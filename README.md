# -Patika_SQL_Egitimi_Odev5
1. Soru: film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en uzun (length) 5 filmi sıralayınız.
+ `select * from film where title like('%n')
order by (length) desc
limit 5`
2. country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.
+ ` select * from country where length(country)>6 and country like '%n'`
3. Soru: film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.
+ ` select title from film where title ilike '%t%t%t%t'`
4. Soru: film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99
olan verileri sıralayınız.
+ ` SELECT * From film Where title LIKE 'C%' AND length > 90 AND rental_rate = 2.99  `
