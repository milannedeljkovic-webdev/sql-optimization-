
---

## 📌 `sql-optimization` – SQL Query Optimization Examples
```markdown
# SQL Optimization Examples  

This repo contains examples of **SQL query optimization techniques** for better performance.  

---

## 📂 Contents  
- Indexing strategies  
- JOIN optimization  
- Aggregation and grouping optimization  
- Execution plan analysis  

---

## 💡 Example  

### ❌ Slow query  
```sql
SELECT * FROM Orders WHERE YEAR(OrderDate) = 2023;

---

✅ Optimized query
CREATE INDEX IX_Orders_OrderDate ON Orders(OrderDate);
SELECT * FROM Orders WHERE OrderDate BETWEEN '2023-01-01' AND '2023-12-31';

---

📫 About Me

Backend Developer with strong skills in C#, .NET, SQL optimization, and performance tuning.
