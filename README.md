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
1. Employee Table
- ![Image](https://github.com/user-attachments/assets/9d797229-c578-4a9d-9e41-9eec050611b9)

## TASK 2
2. Department Table
- ![Image](https://github.com/user-attachments/assets/3943d3ae-7b16-4ac8-9fcd-ea3a935107bf)

## TASK 3
3. Employee Department Table
- ![Image](https://github.com/user-attachments/assets/7c0d9e00-be51-4f32-bf15-b47c1db7cfbe)

## TASK 4
4. Employee Project Table
- ![Image](https://github.com/user-attachments/assets/2065f412-b9f0-45f8-9bd7-bbe88298b244)

## TASK 5
5. Manager Table
- ![Image](https://github.com/user-attachments/assets/11885937-bb10-4287-ada6-c3b0074dfd21)

## EER Diagram 
- ![Image](https://github.com/user-attachments/assets/b8c42cda-fe0b-420f-92de-d9a7e531f3f3)
