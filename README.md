# Sql-dev3
.

1) country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.
2) country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.
3) film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.
4) film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.

****************************************************************************************************************************************************************************
1) --SELECT * FROM country
--WHERE country ILIKE 'A%a';

3)--SELECT * FROM country
--WHERE country LIKE '_____n';

4)--SELECT title FROM film
--WHERE title ILIKE '%t%'
--LIMIT 4;

5)-- SELECT * FROM film
--WHERE title LIKE 'C%'
-- AND length > 90
-- AND rental_rate = 2.99;
