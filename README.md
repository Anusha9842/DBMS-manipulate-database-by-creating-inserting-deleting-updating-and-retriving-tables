SQL> CREATE DATABASE Test; 
Database Created 
SQL> CREATE TABLE Employee(EmployeeNo char(4), EmployeeName varchar2(30),         
EmployeeSal number(10,2),   EmployeeCity varchar2(30), EmployeeDob date); 
Table Created 
SQL> INSERT INTO Employee values('2', 'Santosh', 5000, 'Delhi','23-DEC-1994'); 
1 row inserted 
SQL>select * from Employee; 
SQL> UPDATE Employee SET EmployeeName='KASHISH' WHERE EmployeeNo=1; 
SQL>SELECT * from Employee; 
SQL>DELETE * from Employee;
