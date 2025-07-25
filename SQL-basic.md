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

| 명령어 | 예시 |
|-------|-------|
| CREATE TABLE   | CREATE TABLE employee <br>( employee_id char(2) PRIMARY KEY, <br>first_name varchar(30) NOT NULL, <br>mobile int);  |
| ALTER TABLE - ADD COLUMN  | 옵션 1. ALTER TABLE employee ADD income bigint; <br>옵션 2. ALTER TABLE employee ADD COLUMN income bigint;   |
| ALTER TABLE - ALTER COLUMN  | MySQL: ALTER TABLE employee MODIFY mobile CHAR(20); <br>DB2: ALTER TABLE employee ALTER COLUMN mobile SET DATA TYPE CHAR(20);  |
| ALTER TABLE - DROP COLUMN   | ALTER TABLE employee <br>DROP COLUMN mobile ;  |
| ALTER TABLE - RENAME COLUMN  | MySQL: ALTER TABLE employee CHANGE COLUMN first_name name VARCHAR(255); <br>DB2: ALTER TABLE employee RENAME COLUMN first_name TO name; |
| TRUNCATE TABLE   | MySQL: TRUNCATE TABLE employee; <br>DB2: TRUNCATE TABLE employee IMMEDIATE ;  |
| DROP TABLE   | DROP TABLE employee ;  |

- **phpMyAdmin** (MySQL)
  - PHP로 작성된 오픈 소스 웹 기반 MySQL/MariaDB 관리 도구
  - 웹 기반 GUI로 터미널 없이도 데이터베이스를 직관적으로 관리 가능
 
- **Cloud Database** 종류
  - **IBM Db2**
  - Databases for PostgreSQL
  - Oracle Database Cloud Service
  - Microsoft Azure SQL Database
  - Amazon Relational Database Services(RDS)
