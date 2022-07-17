# **Hacker Rank SQL problems**

## **Easy Problems**

### **1. Select All**

Query all columns (attributes) for every row in the **CITY** table.

The **CITY** table is described as follows:

![hackerrank1](https://github.com/nxtbyt/graphics/blob/main/images/hackerrank1.jpg?raw=true)

**Solution:**

```sql
select
  *
from
  city;
```

### **2. Revising the Select Query I**

Query all columns for all American cities in the **CITY** table with populations larger than **100000**. The **CountryCode** for America is **USA**.

The **CITY** table is described as follows:

![hackerrank2](https://github.com/nxtbyt/graphics/blob/main/images/hackerrank2.jpg?raw=true)

**Solution:**

```sql
select
  *
from
  city
where
  population > 100000
  and countrycode = 'USA';
```