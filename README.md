# SQL-DEV-3
patika.dev linkim: https://app.patika.dev/cmilakonur <br />

1- country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' <br />
karakteri ile sonlananları sıralayınız. <br />
SELECT country FROM country WHERE country LIKE 'A%a' <br />

2- country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' <br />
karakteri ile sonlananları sıralayınız. <br />
SELECT country FROM country WHERE country LIKE '_____%n' <br />

3- film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin <br />
'T' karakteri içeren film isimlerini sıralayınız. <br />
SELECT title FROM film WHERE title ILIKE '%T%%T%%T%%T%' <br />

4- film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan  <br />
büyük olan ve rental_rate 2.99 olan verileri sıralayınız. <br />
SELECT * FROM film WHERE title LIKE 'c%' AND  length>90 AND rental_rate =2.99 <br />
