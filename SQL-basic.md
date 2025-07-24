## **SQL : Basic**

| 명령어 | 예시 |
|-------|-------|
| SELECT   | SELECT city FROM placeofinterest;  |
| WHERE   | SELECT * FROM placeofinterest WHERE city = 'Rome' ;   |
| COUNT   | SELECT COUNT(country) FROM placeofinterest WHERE country='Canada';  |
| DISTINCT   | SELECT DISTINCT country FROM placeofinterest WHERE type='historical';  |
| LIMIT   | SELECT * FROM placeofinterest WHERE airport="pearson" LIMIT 5; |
| INSERT   | INSERT INTO placeofinterest (name,type,city,country,airport) VALUES('Niagara Waterfalls','Nature','Toronto','Canada','Pearson');  |
| UPDATE   | UPDATE placeofinterest SET name = 'Niagara Falls' WHERE name = "Niagara Waterfalls";  |
| DELETE   | DELETE FROM placeofinterest WHERE city IN ('Rome','Vienna'); |
