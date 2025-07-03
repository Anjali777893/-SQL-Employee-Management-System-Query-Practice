# -SQL-Employee-Management-System-Query-Practice

A beginner-friendly SQL practice project simulating real-world employee data operations—covering everything from table creation to schema evolution and KPI queries.


🚀 About the Project
This project is built to strengthen my foundational SQL skills by creating and managing an employees table. It walks through real-world operations like:
- Inserting, filtering, and updating employee records
- Applying constraints like salary checks and age restrictions
- Altering table structure on the fly (adding emails, renaming columns)
- Writing DML and DDL operations from scratch
Whether you're learning SQL, interviewing for a data role, or brushing up your skills—this is a hands-on guide to get your logic flowing.

⚙️ Tech Stack
- PostgreSQL (or any SQL-compliant DBMS)
- Query Editor: pgAdmin, VS Code, DBeaver, or CLI
- SQL language: DDL & DML commands


✅ Features Practiced
- ✔️ CREATE TABLE with constraints
- ✔️ INSERT INTO with multiple rows
- ✔️ SELECT with filters & sorting
- ✔️ UPDATE and DELETE using conditions
- ✔️ ALTER TABLE for schema evolution
- ✔️ DAX-like query logic for AOV, profit, etc.

🧪 Highlight Queries

-- 1. Increase salary for IT employees by 10%
UPDATE employees
SET salary = salary + (salary * 0.1)
WHERE dept_name = 'IT';

-- 2. Retrieve names of employees who joined after Jan 2021
SELECT first_name, last_name
FROM employees
WHERE joining_date > '2021-01-01';

-- 3. Rename department to dept_name
ALTER TABLE employees
RENAME COLUMN department TO dept_name;



📊 Bonus Idea

Want to add flair? Create a simple Power BI or Excel visualization showing:
- Department-wise salary totals
- Employees added per year
- Average age across teams
Add these visuals in the /assets folder and link them in the README!

📌 How to Run

- Clone this repo
- Open employee_table creation.sql in your SQL IDE
- Execute queries section by section
- Modify and experiment—this project is a sandbox!

📬 Contact
Loved the project? Have suggestions? Let’s connect on LinkedIn or shoot a message!


