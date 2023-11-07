# sql-challenge
## Data Modeling
![Data Modeling](https://github.com/jbrents100/sql-challenge/blob/main/EmployeesSQL/schema.png)

## Data Engineering
The schemas for creating the six tables in the data base can be found in [schema.sql](https://github.com/jbrents100/sql-challenge/blob/main/EmployeesSQL/queries.sql)

* `dept_no` and `title_id/emp_title_id` and `sex` are VARCHARs because they have a fixed length.
* All other strings are TEXT because they could have a variable length.
* `first_name` and `last_name` could potentially be NULL as there is no guarantee that a person has a name. However, for this data set, I will be using NOT NULL.

## Data Analysis
The queries to get answers to the data analysis lists are found in [queries.sql](https://github.com/jbrents100/sql-challenge/blob/main/EmployeesSQL/queries.sql)

Number of results for each query

1. 300,024
2. 36,150
3. 24
4. 331,603
5. 20
6. 52,245
7. 137,952
8. 1,638

  - All last names appeared between 145 ('Sadowsky') and 226 ('Baba') times except 'Foolsday' which appeared only once.
