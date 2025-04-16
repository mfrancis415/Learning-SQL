# Learning SQL in 7 Weeks

This repository contains SQL exercises from the [7 Week](#) challenge., using PostgreSQL.

## 📚 Week 1: Core Concepts

### ✅ Variables and Expressions
- Simulated variables using aliases and CTEs
- Performed arithmetic and labeled results using `AS`
- Used `CASE WHEN` for conditional logic
- Created a sentence using string concatenation (`||` in PostgreSQL, `CONCAT()` in MySQL)

**Example:**
```sql
SELECT 
  'Monica' AS name,
  16 AS age,
  65 AS target_age,
  65 - 16 AS years_remaining,
  CONCAT('Monica will reach 65 in ', 65 - 16, ' years.') AS message;
