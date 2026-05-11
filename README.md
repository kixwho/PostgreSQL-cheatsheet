# PostgreSQL-cheatsheet

| Operator  | Function | Example |
| ------------- | ------------- | ------------- |
| =  | Equal to  | WHERE school = 'USC'  |
| <>  | Not equal to  | WHERE school <> 'UCLA'  |
| >  | Greater than  | WHERE salary > 20000  |
| <  | Less than  | WHERE salary < 60500  |
| >=  | Greater than or equal to  | WHERE salary >= 20000  |
| <=  | Less than or equal to  | WHERE salary <= 60500  |
| BETWEEN  | Within a range  | WHERE salary BETWEEN 20000 AND 40000  |
| IN  | Match one of a set of values  | WHERE last_name IN ('Bush', 'Roush')  |
| LIKE  | Match a pattern (case sensitive)  | WHERE first_name LIKE 'Sam%'  |
| Content Cell  | Content Cell  | Content Cell  |
| NOT  | Negates a condition  | WHERE first_name NOT ILIKE 'sam%'  |
| \|\|  | CONCAT within the same row  | SELECT name \|\| ' works as a ' \|\| job  |
| Content Cell  | Content Cell  | Content Cell  |
