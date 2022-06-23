# SQL-Learning
# 1.The company is going to give all employees a 20% increase in their salaries, and your task is to display a list of all of the employees which includes the employee id, the name, the current salary, and the salary they will have after the 20% increase.
```
SELECT
    id,
    name,
    salary AS old_salary,
    salary * 1.20 "new salary"
FROM employee e;
```
