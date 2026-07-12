<img width="562.4" height="167" alt="image" src="https://github.com/user-attachments/assets/1b193a97-2281-429c-8af4-a96f4f744d45" />

| Operator  | Function | Example |
| ------------- | ------------- | ------------- |
| =  | Equal to  | WHERE school = 'USC'  |
| <> or !=  | Not equal to  | WHERE school <> 'UCLA'  |
| >  | Greater than  | WHERE salary > 20000  |
| <  | Less than  | WHERE salary < 60500  |
| >=  | Greater than or equal to  | WHERE salary >= 20000  |
| <=  | Less than or equal to  | WHERE salary <= 60500  |
| BETWEEN  | Within a range  | WHERE salary BETWEEN 20000 AND 40000  |
| IN  | Match one of a set of values  | WHERE last_name IN ('Bush', 'Roush')  |
| LIKE  | Match a pattern (case sensitive)  | WHERE first_name LIKE 'Sam%'  |
| ILIKE  | Match a pattern (case insensitive)  | WHERE first_name ILIKE 'sam%'  |
| NOT  | Negates a condition  | WHERE first_name NOT ILIKE 'sam%'  |
| \|\|  | CONCAT within the same row  | SELECT name \|\| ' works as a ' \|\| job  |
| ~  | Matches regular expression  | WHERE product_code ~ '^[A-Z]{2}[0-9]{4}$'  |
