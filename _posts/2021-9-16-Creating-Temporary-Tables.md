---
layout: post
title:  "Create Temporary Tables" 
categories: sql
tags: creating temp table
---

# Why Create Temporary Tables?

- `temporary tables` will be deleted when current `session is terminated`.
- Fater than creating a real table
- useful for complex queries using subset and joins


# How to Create a Temporary Table 
Syntax of creating a temporary table 
```sql
CREATE TEMPORARY TABLE Sandals AS (
    SELECT * FROM shoes WHERE shoe_type = 'sandals'
)
```
In SQLite Syntax 
![alt text](../../../../images/create_temp_table_syntax.png)
