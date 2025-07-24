## **SQL : Basic**

| 명령어 | 예시 |
|-------|-------|
| SELECT   | SELECT city FROM placeofinterest;  |
| WHERE   | SELECT * <br>FROM placeofinterest <br>WHERE city = 'Rome' ;   |
| COUNT   | SELECT COUNT(country) <br>FROM placeofinterest <br>WHERE country='Canada';  |
| DISTINCT   | SELECT DISTINCT country <br>FROM placeofinterest <br>WHERE type='historical';  |
| LIMIT   | SELECT * <br>FROM placeofinterest <br>WHERE airport="pearson" LIMIT 5; |
| INSERT   | INSERT INTO placeofinterest (name,type,city,country,airport) <br>VALUES('Niagara Waterfalls','Nature','Toronto','Canada','Pearson');  |
| UPDATE   | UPDATE placeofinterest <br>SET name = 'Niagara Falls' <br>WHERE name = "Niagara Waterfalls";  |
| DELETE   | DELETE FROM placeofinterest <br>WHERE city IN ('Rome','Vienna'); |
