# Librarymanagement2
# 📚 Task 2: Data Insertion and Handling NULLs

## 📌 Objective
DML and NULL handling
To practice **inserting**, **updating**, and **deleting** data in SQL tables. The focus is on handling **`NULL` values**, ensuring referential integrity, and using `WHERE` conditions effectively.

---

## 🛠️ Tools Used
- MySQL Workbench  
- DB Fiddle / SQLiteStudio (alternatives)
- SQL (DDL & DML)
---

## Database Tables Involved

### 🔸 1. `Author`
### 🔸 2. `Book`
### 🔸 3. `Member`
### 🔸 4. `Loan`
---

##  Operations Performed
⚠️ Common Mistakes to Avoid
Trying to insert into a table with a foreign key before inserting into the referenced table.

### 🔹 INSERT
- Inserted data into all 4 tables.
### 🔹 Handle missing values using NULL or default
-- Used `NULL` for:
  - `author_id` (in some books)
  - `join_date` (in some members)
  - `return_date` (in ongoing loans)
### 🔹UPDATE with WHERE Conditions
  -Updated values that were initially inserted as NULL:
### 🔹DELETE
  -🗑️ Deleted all data from Author and Book tables 


⚠️ Challenges Faced & Solutions
AUTO_INCREMENT Issue:
AUTO_INCREMENT did not restart from 1 automatically.

Solution: Manually reset using:
 -Alert 

📈 Outcome
✅ Understood how to manage NULL values during insert and update operations.
✅ Learned proper order of operations when working with PK–FK relationships.
✅ Successfully reset auto-increment values after table truncation.

