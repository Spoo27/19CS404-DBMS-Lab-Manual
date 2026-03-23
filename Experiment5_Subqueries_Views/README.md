# Experiment 5: Subqueries and Views

## AIM
To study and implement subqueries and views.

## THEORY

### Subqueries
A subquery is a query inside another SQL query and is embedded in:
- WHERE clause
- HAVING clause
- FROM clause

**Types:**
- **Single-row subquery**:
  Sub queries can also return more than one value. Such results should be made use along with the operators in and any.
- **Multiple-row subquery**:
  Here more than one subquery is used. These multiple sub queries are combined by means of ‘and’ & ‘or’ keywords.
- **Correlated subquery**:
  A subquery is evaluated once for the entire parent statement whereas a correlated Sub query is evaluated once per row processed by the parent statement.

**Example:**
```sql
SELECT * FROM employees
WHERE salary > (SELECT AVG(salary) FROM employees);
```
### Views
A view is a virtual table based on the result of an SQL SELECT query.
**Create View:**
```sql
CREATE VIEW view_name AS
SELECT column1, column2 FROM table_name WHERE condition;
```
**Drop View:**
```sql
DROP VIEW view_name;
```

**Question 1**

<img width="942" height="559" alt="image" src="https://github.com/user-attachments/assets/28be8da1-926e-4b23-a4f4-95aee1a0cca4" />

**Output:**

<img width="1338" height="964" alt="image" src="https://github.com/user-attachments/assets/5af40273-77d1-4f3e-a16b-e6558d084a17" />

**Question 2**

<img width="817" height="393" alt="image" src="https://github.com/user-attachments/assets/558f0cbc-b9cc-44d7-b663-27a062c9954e" />

**Output:**

<img width="1326" height="845" alt="image" src="https://github.com/user-attachments/assets/14fe7467-26a4-4a3f-b954-dd9bfaeae582" />

**Question 3**

<img width="1057" height="596" alt="image" src="https://github.com/user-attachments/assets/ae63d315-0000-4104-9c2f-6b8e4f0fc9c3" />

**Output:**

<img width="1340" height="868" alt="image" src="https://github.com/user-attachments/assets/42ed423a-8697-4230-880c-bb0f51c79760" />

**Question 4**

<img width="964" height="453" alt="image" src="https://github.com/user-attachments/assets/d8084161-184b-45f9-8fc1-7c533f3dc9cf" />

**Output:**

<img width="1343" height="816" alt="image" src="https://github.com/user-attachments/assets/e13c11df-969a-4d10-b865-fed217d7a2a0" />

**Question 5**

<img width="928" height="335" alt="image" src="https://github.com/user-attachments/assets/3347f3dd-fff0-4090-8212-90f8da2eeb3a" />

**Output:**

<img width="1337" height="818" alt="image" src="https://github.com/user-attachments/assets/4497fd7c-5a25-4a44-bde3-54f41f7ff93d" />

**Question 6**

<img width="883" height="367" alt="image" src="https://github.com/user-attachments/assets/f11437c2-bc97-4759-87c3-15618cbb8bc2" />

**Output:**

<img width="1337" height="803" alt="image" src="https://github.com/user-attachments/assets/648d3fd3-7ed4-489d-b267-b62c6b2f54bd" />

**Question 7**

<img width="890" height="505" alt="image" src="https://github.com/user-attachments/assets/3878269e-9136-4f40-ad46-ed5360ff44f0" />

**Output:**

<img width="1334" height="755" alt="image" src="https://github.com/user-attachments/assets/7ee5aa23-bcee-4a1c-be05-53792da8e24a" />

**Question 8**

<img width="918" height="412" alt="image" src="https://github.com/user-attachments/assets/a6c4aeae-c6a5-4161-9663-53a5cb0fc7d4" />

**Output:**

<img width="1338" height="855" alt="image" src="https://github.com/user-attachments/assets/02566ecd-3fb5-4e87-8264-c6a37126f6bf" />

**Question 9**

<img width="1079" height="474" alt="image" src="https://github.com/user-attachments/assets/51296133-59b7-4576-a4b6-7bd74e943b57" />

**Output:**

<img width="1347" height="821" alt="image" src="https://github.com/user-attachments/assets/969d77f3-ab07-4c4b-a518-dadb26d9bd15" />

**Question 10**

<img width="928" height="467" alt="image" src="https://github.com/user-attachments/assets/6c81b0d2-c752-41be-973a-7ad0e5627c64" />

**Output:**

<img width="1338" height="833" alt="image" src="https://github.com/user-attachments/assets/1437bea0-64b7-40b4-afc4-60b65fea2f87" />

## RESULT
Thus, the SQL queries to implement subqueries and views have been executed successfully.
