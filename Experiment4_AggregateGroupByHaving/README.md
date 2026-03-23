# Experiment 4: Aggregate Functions, Group By and Having Clause

## AIM
To study and implement aggregate functions, GROUP BY, and HAVING clause with suitable examples.

## THEORY

### Aggregate Functions
These perform calculations on a set of values and return a single value.

- **MIN()** – Smallest value  
- **MAX()** – Largest value  
- **COUNT()** – Number of rows  
- **SUM()** – Total of values  
- **AVG()** – Average of values

**Syntax:**
```sql
SELECT AGG_FUNC(column_name) FROM table_name WHERE condition;
```
### GROUP BY
Groups records with the same values in specified columns.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name;
```
### HAVING
Filters the grouped records based on aggregate conditions.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name
HAVING condition;
```

**Question 1**

<img width="945" height="387" alt="image" src="https://github.com/user-attachments/assets/600dfe77-e147-40fe-942f-eb89e68034ae" />

**Output:**

<img width="1302" height="959" alt="image" src="https://github.com/user-attachments/assets/fc13462c-442c-4b8f-99ee-2f808cc68a48" />

**Question 2**

<img width="1097" height="424" alt="image" src="https://github.com/user-attachments/assets/414f8896-3ac9-463a-add4-4a0d13a6416e" />

**Output:**

<img width="1312" height="997" alt="image" src="https://github.com/user-attachments/assets/99b64388-39c3-4496-ab72-ff1769d9bfc1" />

**Question 3**

<img width="877" height="442" alt="image" src="https://github.com/user-attachments/assets/8d07d738-073e-4c1d-a3ee-aad230434511" />

**Output:**

<img width="1328" height="909" alt="image" src="https://github.com/user-attachments/assets/5cff023b-3918-4228-bbb2-982fd2c42501" />

**Question 4**

<img width="899" height="389" alt="image" src="https://github.com/user-attachments/assets/e9a90b7d-3db1-4a20-a503-58e1643d01a4" />

**Output:**

<img width="1296" height="748" alt="image" src="https://github.com/user-attachments/assets/46c3387e-eccf-472a-849c-911481a80043" />

**Question 5**

<img width="1024" height="362" alt="image" src="https://github.com/user-attachments/assets/148284f6-4f1d-40ca-84c2-195100d8177c" />

**Output:**

<img width="1304" height="752" alt="image" src="https://github.com/user-attachments/assets/9deec0ff-db0b-431a-86d4-0e85f97b5f04" />

**Question 6**

<img width="761" height="371" alt="image" src="https://github.com/user-attachments/assets/773e63ff-8ca9-48c3-ba2c-1bda69e03f17" />

**Output:**

<img width="1314" height="745" alt="image" src="https://github.com/user-attachments/assets/5d8ebcff-c6e2-4b8e-8800-fb3fa482c38a" />

**Question 7**

<img width="784" height="358" alt="image" src="https://github.com/user-attachments/assets/277c4648-536f-419b-ac62-d5c9ffb8b685" />


**Output:**

<img width="1310" height="761" alt="image" src="https://github.com/user-attachments/assets/1029c93c-8caa-421e-99bb-d552eb98c9f8" />

**Question 8**

<img width="1316" height="360" alt="image" src="https://github.com/user-attachments/assets/5bab64c3-4609-4c94-b496-8bdc1735ea0b" />

**Output:**

<img width="1313" height="747" alt="image" src="https://github.com/user-attachments/assets/4561a67a-886e-4670-ad3f-a3360d299922" />

**Question 9**

<img width="1295" height="382" alt="image" src="https://github.com/user-attachments/assets/d3130358-8af9-4d71-92f2-3ca303bb1e7b" />

**Output:**

<img width="1305" height="826" alt="image" src="https://github.com/user-attachments/assets/8f556aa8-6247-43f5-be25-fcd53f418aa0" />

**Question 10**

<img width="1292" height="382" alt="image" src="https://github.com/user-attachments/assets/4f728ab2-1af4-47f3-82d7-feae8b4bda01" />

**Output:**

<img width="1309" height="786" alt="image" src="https://github.com/user-attachments/assets/b964fec2-4ed7-4676-acd7-28e36f318e05" />

## RESULT
Thus, the SQL queries to implement aggregate functions, GROUP BY, and HAVING clause have been executed successfully.
