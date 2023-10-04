# Ex-No-4-Creating-Procedures-using-PL-SQL

AIM: To create a procedure using PL/SQL.

Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table
## Program:
```
SQL> CREATE TABLE ep(
     empid NUMBER,
     empname VARCHAR(10),
     dept VARCHAR(10),
     salary NUMBER
    );
CREATE OR REPLACE PROCEDURE emp_data AS
    BEGIN
    INSERT INTO ep(empid,empname,dept,salary)
    values(1,'john','MD',10000000);
    INSERT INTO ep(empid,empname,dept,salary)
    values(2,'ARUN','HR',500000);
    INSERT INTO ep(empid,empname,dept,salary)
    values(3,'Ravi','IT',200000);
    COMMIT;
   END;
  /
```

  ## output:
  ![image](https://github.com/Thenmozhi-Palanisamy/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/95198708/7f473885-ac38-4a15-a5c8-5d6b62949964)

  
  ## Result:
  THE PROGRAM HAS BEEN IMPLEMENTED SUCCESSFULLY
