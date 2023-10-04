# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: 
To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```
create or replace procedure insert_emp_data AS
begin
insert into employeetbl1 (Empid,Empname,Dept,Salary)
values (1,'VASUNDRA','Finance',60000);
insert into employeetbl1 (Empid,Empname,Dept,Salary)
values (2,'SARAH','MD',65000);
insert into employeetbl1 (Empid,Empname,Dept,Salary)
values (3,'RAJU','HR',75000);
commit;
end;
/
Procedure created.

begin
insert_emp_data;
end;
/

PL/SQL procedure successfully completed.
```
### Output:
![3](https://github.com/vasundrasriravi/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119393983/4f84b45b-31ff-40d1-b553-c94d3345f547)

![3 1](https://github.com/vasundrasriravi/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119393983/8fd9339e-6de5-4c5c-a91d-461917a851f1)

### Result:
To create a procedure using PL/SQL is executed successfully.
