# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
##DATE:11/8/23
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```

## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b32bceb5-9f0f-4c30-b27f-c4375e677f46)



### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/3fd9b83b-a6e7-4e47-b0cb-f2815bbbae95)


### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/15e1ebf0-899f-4589-aee8-0ea4570cefba)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/ad0c2970-47bc-4591-8f4b-a295a38b092d)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/72faf04a-7d00-4070-8b1b-433f67d05a51)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b697b096-ba16-4329-ac6b-d015128fd061)


### Q5)	List the names of Clerks from emp table.


### QUERY:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/61599008-03dd-4cd8-b16b-aaec28ff1c71)


### OUTPUT:

![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/6c893a4a-2f5d-4dab-ac46-1f936a3e945b)



### Q6)	List the names of employee who are not Managers.


### QUERY:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/651f2524-e646-4f36-ac52-608e7b43fa8c)

### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/865bc670-1d51-48d0-9097-7b337e8f934e)


### Q7)	List the names of employees not eligible for commission.


### QUERY:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/187ed43d-cd42-4117-a295-a453760159ee)


### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/33370cdd-bd30-4bc6-bc47-311adef3fdf9)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/fd18056e-dcf7-45fa-b12f-65970eb6c315)


### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/b7c22066-00f6-456f-9256-42f25484b9ac)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/241dfac7-f8f2-4322-9c77-7b8e9cd7b1c6)


### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/9bc25008-a4f9-45af-b8ca-b9853b6234fd)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/faa72449-b9a9-4b80-9f25-00999ee56ec6)


### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/a52bc108-08c6-4121-ad09-cd5f03a685e0)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/345fce90-263f-4253-87ff-65c4be435d55)


### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/def9ef76-fe71-4f30-b6c9-b792b181fb72)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/d190a382-3bf9-406c-a3ca-cacd5a86e6c0)


### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/11641e2d-5489-44e0-b8fa-f2eee31556d9)


### Q13) Find number of rows in the table EMP

### QUERY:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/ed2190ec-eb76-4c3c-b400-11903f825662)


### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/69caa005-a8b3-4a58-b6d0-1e2be1a13d56)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/ce7ab90b-ae51-4568-9c33-3808a5ab9bf3)


### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/e564effb-47b1-4059-a9b0-61f70de81180)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/865695c3-e280-4b1c-b856-7adce1047297)


### OUTPUT:
![image](https://github.com/RANJEETH17/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/120718823/177fe9cc-6ed9-4ef8-82cf-75e3dd358355)

### RESULT:
QUERIES EXECUTED SUCCESSFULLY.
