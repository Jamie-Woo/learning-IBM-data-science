## **SQL : Basic**

| 명령어 | 예시 |
|-------|-------|
| **SELECT**   | SELECT city FROM placeofinterest;  |
| **WHERE**   | SELECT * <br>FROM placeofinterest <br>WHERE city = 'Rome' ;   |
| **COUNT**   | SELECT COUNT(country) <br>FROM placeofinterest <br>WHERE country='Canada';  |
| **DISTINCT**   | SELECT DISTINCT country <br>FROM placeofinterest <br>WHERE type='historical';  |
| **LIMIT**   | SELECT * <br>FROM placeofinterest <br>WHERE airport="pearson" <br>**LIMIT** 5; |
| **INSERT**   | **INSERT INTO** placeofinterest (name,type,city,country,airport) <br>VALUES('Niagara Waterfalls','Nature','Toronto','Canada','Pearson');  |
| **UPDATE**   | **UPDATE** placeofinterest <br>SET name = 'Niagara Falls' <br>WHERE name = "Niagara Waterfalls";  |
| **DELETE**   | **DELETE FROM** placeofinterest <br>WHERE city IN ('Rome','Vienna'); |

| 명령어 | 예시 |
|-------|-------|
| **CREATE TABLE**   | CREATE TABLE employee <br>( employee_id char(2) PRIMARY KEY, <br>first_name varchar(30) NOT NULL, <br>mobile int);  |
| **ALTER TABLE - ADD COLUMN**  | 옵션 1. ALTER TABLE employee ADD income bigint; <br>옵션 2. ALTER TABLE employee ADD COLUMN income bigint;   |
| **ALTER TABLE - ALTER COLUMN**  | MySQL: ALTER TABLE employee MODIFY mobile CHAR(20); <br>DB2: ALTER TABLE employee ALTER COLUMN mobile SET DATA TYPE CHAR(20);  |
| **ALTER TABLE - DROP COLUMN**   | ALTER TABLE employee <br>DROP COLUMN mobile ;  |
| **ALTER TABLE - RENAME COLUMN**  | MySQL: ALTER TABLE employee CHANGE COLUMN first_name name VARCHAR(255); <br>DB2: ALTER TABLE employee RENAME COLUMN first_name TO name; |
| **TRUNCATE TABLE**   | MySQL: TRUNCATE TABLE employee; <br>DB2: TRUNCATE TABLE employee IMMEDIATE ;  |
| **DROP TABLE**   | DROP TABLE employee ;  |

| 명령어 | 예시 |
|-------|-------|
| **LIKE**   | SELECT f_name , l_name FROM employees WHERE address <br>**LIKE** '%Elgin,IL%';  |
| **BETWEEN** | SELECT * FROM employees WHERE salary <br>**BETWEEN** 40000 AND 80000;  |
| **ORDER BY**  | SELECT f_name, l_name, dep_id FROM employees <br>**ORDER BY** dep_id DESC, l_name; |
| **GROUP BY** | SELECT dep_id, COUNT(*) FROM employees <br>**GROUP BY** dep_id;  |
| **HAVING** | SELECT DEP_ID, COUNT(*) AS "NUM_EMPLOYEES", AVG(SALARY) AS "AVG_SALARY" FROM EMPLOYEES GROUP BY DEP_ID <br>**HAVING** count(*) < 4 <br>ORDER BY AVG_SALARY; |

| 명령어 | 예시 |
|-------|-------|
| **COUNT**  | SELECT COUNT(dep_id) FROM employees;  |
| **AVG**  |  SELECT AVG(salary) FROM employees; |
| **SUM** | SELECT SUM(salary) FROM employees;  |
| **MIN**  | SELECT MIN(salary) FROM employees;  |
| **MAX**  | SELECT MAX(salary) FROM employees; |
| **ROUND** | SELECT ROUND(salary) FROM employees;  |
| **LENGTH** | SELECT LENGTH(f_name) FROM employees;  |
| **UCASE**  | SELECT UCASE(f_name) FROM employees;  |
| **LCASE** | SELECT LCASE(f_name) FROM employees;  |
| **DISTINCT**  | SELECT DISTINCT UCASE(f_name) FROM employees;  |
| **DAY**  | SELECT DAY(b_date) FROM employees where emp_id = 'E1002';  |
| **CURRENT_DATE**  |  SELECT CURRENT_DATE; |
| **DATEDIFF()**  | SELECT DATEDIFF(CURRENT_DATE, date_column) FROM table;  |
| **FROM_DAYS()**  | SELECT FROM_DAYS(DATEDIFF(CURRENT_DATE, date_column)) FROM table;  |
| **DATE_ADD()** | SELECT DATE_ADD(date, INTERVAL 3 DAY);  |
| **DATE_SUB()**  | SELECT DATE_SUB(date, INTERVAL 3 DAY);  |
| **Subquery**  | SELECT emp_id, f_name, l_name, salary <br>FROM employees <br>where salary < (SELECT AVG(salary) FROM employees);  |
| **Implicit Inner Join** <br>(암묵적 내부 조인)  | SELECT * <br>FROM employees, jobs <br>where employees.job_id = jobs.job_ident;  |
| **Implicit Cross Join**  | SELECT * <br>FROM employees, jobs;  |
---

- **phpMyAdmin** (MySQL)
  - PHP로 작성된 오픈 소스 웹 기반 MySQL/MariaDB 관리 도구
  - 웹 기반 GUI로 터미널 없이도 데이터베이스를 직관적으로 관리 가능
 
- **Cloud Database** 종류
  - **IBM Db2**
  - Databases for PostgreSQL
  - Oracle Database Cloud Service
  - Microsoft Azure SQL Database
  - Amazon Relational Database Services(RDS)
