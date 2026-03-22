# Experiment 2: DDL Commands

## AIM
To study and implement DDL commands and different types of constraints.

## THEORY

### 1. CREATE
Used to create a new relation (table).

**Syntax:**
```sql
CREATE TABLE (
  field_1 data_type(size),
  field_2 data_type(size),
  ...
);
```
### 2. ALTER
Used to add, modify, drop, or rename fields in an existing relation.
(a) ADD
```sql
ALTER TABLE std ADD (Address CHAR(10));
```
(b) MODIFY
```sql
ALTER TABLE relation_name MODIFY (field_1 new_data_type(size));
```
(c) DROP
```sql
ALTER TABLE relation_name DROP COLUMN field_name;
```
(d) RENAME
```sql
ALTER TABLE relation_name RENAME COLUMN old_field_name TO new_field_name;
```
### 3. DROP TABLE
Used to permanently delete the structure and data of a table.
```sql
DROP TABLE relation_name;
```
### 4. RENAME
Used to rename an existing database object.
```sql
RENAME TABLE old_relation_name TO new_relation_name;
```
### CONSTRAINTS
Constraints are used to specify rules for the data in a table. If there is any violation between the constraint and the data action, the action is aborted by the constraint. It can be specified when the table is created (using CREATE TABLE) or after it is created (using ALTER TABLE).
### 1. NOT NULL
When a column is defined as NOT NULL, it becomes mandatory to enter a value in that column.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) NOT NULL
);
```
### 2. UNIQUE
Ensures that values in a column are unique.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) UNIQUE
);
```
### 3. CHECK
Specifies a condition that each row must satisfy.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) CHECK (logical_expression)
);
```
### 4. PRIMARY KEY
Used to uniquely identify each record in a table.
Properties:
Must contain unique values.
Cannot be null.
Should contain minimal fields.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) PRIMARY KEY
);
```
### 5. FOREIGN KEY
Used to reference the primary key of another table.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size),
  FOREIGN KEY (column_name) REFERENCES other_table(column)
);
```
### 6. DEFAULT
Used to insert a default value into a column if no value is specified.

Syntax:
```sql
CREATE TABLE Table_Name (
  col_name1 data_type,
  col_name2 data_type,
  col_name3 data_type DEFAULT 'default_value'
);
```

**Question 1**

<img width="1231" height="618" alt="image" src="https://github.com/user-attachments/assets/eca8654c-3fac-4a1d-9d4f-f5edb579a633" />


**Output:**
 <img width="1180" height="882" alt="image" src="https://github.com/user-attachments/assets/ab9b41c6-34ad-4377-bca6-3d8de65ffe6d" />


**Question 2**
<img width="1226" height="299" alt="image" src="https://github.com/user-attachments/assets/6e71d1c2-fb92-4c92-8f0e-02d74d3965c8" />

**Output:**
<img width="1175" height="787" alt="image" src="https://github.com/user-attachments/assets/7c106437-b197-4348-8b2b-7ba3d173f6dc" />

**Question 3**

<img width="1259" height="418" alt="image" src="https://github.com/user-attachments/assets/f76b4fae-6db5-4096-b2d6-209df52b1b5b" />


**Output:**

<img width="1180" height="853" alt="image" src="https://github.com/user-attachments/assets/cec847e1-061f-4d4b-9e68-8a5b554233ec" />


**Question 4**

<img width="1230" height="422" alt="image" src="https://github.com/user-attachments/assets/47b2727e-dcd7-4c75-b9dc-6c3f46cdec0e" />


**Output:**

<img width="1194" height="900" alt="image" src="https://github.com/user-attachments/assets/4b9f05d8-1756-4975-b443-bcbaa26d443e" />


**Question 5**

<img width="1224" height="639" alt="image" src="https://github.com/user-attachments/assets/73ce8844-daf4-4218-ab94-bf53dc72e630" />


**Output:**

<img width="1214" height="917" alt="image" src="https://github.com/user-attachments/assets/d3433b94-0420-4551-b0fe-7ff096751467" />


**Question 6**
<img width="1199" height="560" alt="image" src="https://github.com/user-attachments/assets/13ba04fe-4553-4c6d-b143-a451318a9052" />

**Output:**

<img width="1208" height="549" alt="image" src="https://github.com/user-attachments/assets/561b4490-bac5-406b-9b5e-11dae0c00ee3" />


**Question 7**

<img width="1234" height="523" alt="image" src="https://github.com/user-attachments/assets/c09a6aff-8c33-4ac3-bc57-994e25b95cfd" />


**Output:**

<img width="1170" height="849" alt="image" src="https://github.com/user-attachments/assets/0d7aa12a-cd19-48e0-9366-26862677ca68" />


**Question 8**

<img width="1071" height="315" alt="Screenshot 2026-02-02 134552" src="https://github.com/user-attachments/assets/c240389c-af12-435f-9180-69e7f02ce1e6" />

**Output:**

<img width="1302" height="669" alt="Screenshot 2026-02-02 134613" src="https://github.com/user-attachments/assets/d677ccec-3570-4636-bb35-083a4ae7358e" />

**Question 9**

<img width="564" height="257" alt="Screenshot 2026-02-02 134704" src="https://github.com/user-attachments/assets/0b7c7800-35cc-4db0-bda1-f97ba03d1388" />

**Output:**

<img width="1260" height="673" alt="Screenshot 2026-02-02 134722" src="https://github.com/user-attachments/assets/c0ed4d93-5ed2-458e-9baa-a1585e0a7950" />

**Question 10**

<img width="656" height="272" alt="Screenshot 2026-02-02 134839" src="https://github.com/user-attachments/assets/52729972-07dc-48c3-8de6-6101d8dfa6d6" />

**Output:**

<img width="1246" height="693" alt="Screenshot 2026-02-02 134818" src="https://github.com/user-attachments/assets/3c6bbf76-3ac9-4aff-a12e-15b02d36e7ae" />

## RESULT
Thus, the SQL queries to implement different types of constraints and DDL commands have been executed successfully.
