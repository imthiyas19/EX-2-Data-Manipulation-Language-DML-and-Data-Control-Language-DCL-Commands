# EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands
### AIM:
To create a manager database and execute DML queries using SQL.

### DML(Data Manipulation Language)
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
## List of DML commands:
INSERT: It is used to insert data into a table.
UPDATE: It is used to update existing data within a table.
DELETE: It is used to delete records from a database table.
##Create the table as given below:                                                                                                                                                                                ```sql create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10)); ```
## insert the following values into the table
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
@@ -30,116 +31,150 @@ insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bo
### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.
## QUERY:
![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/9b233c82-eefd-40b2-9533-8c7bbf1cc119)
### OUTPUT:
![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/59a7f1a7-0fc6-4c6a-b64c-6ba2b10dc193)
## Q2) Delete the records from manager table where the salary less than 2750.
# QUERY:
![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/432cea83-3b65-4380-982f-68f580ae0221)
# OUTPUT
![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/bfa1175f-78a8-4619-8eea-5720d21d9811)
# Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)
# QUERY:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/0ac6119f-a7ce-4081-80a5-6873854b2676)




# OUTPUT:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/849b3d1f-f4ee-43fa-8796-556b5a9c484f)



# Q5) List the names of Clerks from emp table.
# QUERY:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/81d50789-83fe-4ea4-9096-f8a1915791b3)


# OUTPUT:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/ca30dbae-38be-4d98-98f9-0eb729a90a58)


# Q6) List the names of employee who are not Managers.
# QUERY:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/d0364cb4-f76c-40ff-88fe-30022c3e56e4)


# OUTPUT:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/fac83175-0974-4de4-93b7-c837bec7a983)


# Q7) List the names of employees not eligible for commission.
# QUERY:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/3f53f4df-d6fb-4217-a56d-858a8510d8cd)


# OUTPUT:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/e7d4d5a0-9ec0-4312-8b92-df77c47d31c0)


# Q8) List employees whose name either start or end with ‘s’.
# QUERY:


![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/da7b07fe-dfd1-4ac7-9597-a47efee20357)

# OUTPUT:


![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/e637d3d5-5877-47ac-92c1-bfed7b2f859f)

# Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.
# QUERY:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/f15b770a-5e47-46a5-b6fd-b93aa6d6547b)


# OUTPUT:


![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/6f644a9a-347f-4177-8d60-2b64ed5feab1)

# Q10) List the Details of Employees who have joined before 30 Sept 81.
# QUERY:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/f4e6bc2c-10c8-4818-aa00-8af3afe64651)


# OUTPUT:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/5b1dbd2e-6c52-4b70-a385-2ade1ff093f7)


# Q11) List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.
# QUERY:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/da5496d5-e836-4e32-904b-cf2f8a1af33b)


# OUTPUT:


![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/75a4e7a1-5497-41e7-ac2b-dafcb59d4edd)

# Q12) List the names of employees not belonging to dept no 30,40 & 10
# QUERY:


![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/4572edab-c8c3-410a-b67c-c3006b6639f8)

# OUTPUT:


![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/305a8bee-1ab0-4500-ab50-348e72c1a060)

# Q13) Find number of rows in the table EMP
# QUERY:


![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/0b55a25c-a858-4d21-9e69-635528b4942c)

# OUTPUT:


![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/039f4202-faac-4c63-bb82-6dcf9bacb28e)

# Q14) Find maximum, minimum and average salary in EMP table.
# QUERY:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/0b08ce6e-e27b-49ad-a3f5-b486400884ff)


# OUTPUT:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/9fe29134-0e16-4ac8-9415-726d7ff94b20)


# Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.
# QUERY:

![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/2a9876b9-2e71-4cd3-ab9f-824289dbd55d)


# OUTPUT:


![image](https://github.com/imthiyas19/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120353416/ddf466f3-ce3f-42a3-bb55-94e33fb6f416)
# RESULT:
To create a manager database and execute DML queries using SQL is executed successfully.
