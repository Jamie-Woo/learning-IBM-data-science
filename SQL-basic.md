## **SQL : Basic**

| 명령어 | 예시 |
|-------|-------|
| SELECT   | SELECT city FROM placeofinterest;  |
| WHERE   | SELECT * <br>FROM placeofinterest <br>WHERE city = 'Rome' ;   |
| COUNT   | SELECT COUNT(country) <br>FROM placeofinterest <br>WHERE country='Canada';  |
| DISTINCT   | SELECT DISTINCT country <br>FROM placeofinterest <br>WHERE type='historical';  |
| LIMIT   | SELECT * <br>FROM placeofinterest <br>WHERE airport="pearson" <br>LIMIT 5; |
| INSERT   | INSERT INTO placeofinterest (name,type,city,country,airport) <br>VALUES('Niagara Waterfalls','Nature','Toronto','Canada','Pearson');  |
| UPDATE   | UPDATE placeofinterest <br>SET name = 'Niagara Falls' <br>WHERE name = "Niagara Waterfalls";  |
| DELETE   | DELETE FROM placeofinterest <br>WHERE city IN ('Rome','Vienna'); |

- Database practicing application : phpMyAdmin (MySQL)
  - PHP로 작성된 오픈 소스 웹 기반 MySQL/MariaDB 관리 도구
  - 웹 기반 GUI로 터미널 없이도 데이터베이스를 직관적으로 관리 가능 
