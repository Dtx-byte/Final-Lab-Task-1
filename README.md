# [Finals-Lab-Task-1]
- This portfolio is about learning MySQL basics through a multi-level company database. It includes tasks like writing SQL queries, creating table structures, and making an ER diagram or relational schema. The portfolio will also include SQL copies of the database and table structures to show how the database is built.

## Step by Step Process
TASK 1- Create the `employees` table:
   - Define `employee_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_name` as a VARCHAR (up to 255 characters), and make it not null.
   - Define `manager_id` as an integer, which will be a foreign key referencing `employee_id` from the same table.

TASK 2- Create the `departments` table:
   - Define `department_id` as a unique integer, auto-increment, and primary key.
   - Define `department_name` as a VARCHAR (up to 255 characters), and make it not null.

TASK 3- Create the `employee_departments` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `department_id` as an integer, which will be a foreign key referencing `department_id` in the `departments` table.
   - Set a composite primary key on the combination of `employee_id` and `department_id`.

TASK 4- Create the `employee_projects` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `project_name` as a VARCHAR (up to 255 characters), and make it not null.

TASK 5- Create the `managers` table:
   - Define `manager_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.

# Code Screenshots and Table Structures
## TASK 1
### Employee Table
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task%201.png)
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task1%20Struc.png)

## TASK 2
### Department Table
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task%202.png)
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task2%20Struc.png)

## TASK 3
### Employee Department Table
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task%203.png)
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task3%20Struc.png)

## TASK 4
### Employee Project Table
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task%204.png)
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task4%20Struc.png)
  
## TASK 5
### Manager Table
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task%205.png)
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/Task5%20Struc.png)

## EER Diagram 
- ![Image](https://github.com/Dtx-byte/Final-Lab-Task-1/blob/main/Images/CompanyDB%20ERD.png)
