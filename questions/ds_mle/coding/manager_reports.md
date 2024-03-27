## Managers with at least 3 direct reports

Given the table schema, write a solution to find managers with at least five direct reports. Return the result table in any order. People cannot be managers of themselves. 

Use **Pandas** for this exercise

<pre>
Table: Employees
+-------------+---------+-----------------------+
| Column Name | Type    | Description           |
+-------------+---------+-----------------------+
| id          | int     | primary key           |
| name        | varchar | name of employee      |
| department  | varchar | employee's department |
| managerId   | int     | manager's id          |
+-------------+---------+-----------------------+
</pre>

The result format is in the following example.

Example 1:

<pre>
Table: Employees
+-----+-------+------------+-----------+
| id  | name  | department | managerId |
+-----+-------+------------+-----------+
| 101 | John  | A          | null      |
| 102 | Dan   | A          | 101       |
| 103 | James | A          | 101       |
| 104 | Amy   | A          | 102       |
| 105 | Anne  | A          | 102       |
| 106 | Ron   | B          | 101       |
| 107 | Jake  | B          | 102       |
+-----+-------+------------+-----------+
</pre>

Output: 
<pre>
+------+
| name |
+------+
| John |
| Dan  |
+------+
</pre>