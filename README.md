# 584.-Find-Customer-Referee
Problem Link : https://leetcode.com/problems/find-customer-referee/description/?envType=study-plan-v2&envId=top-sql-
## Solution

```sql
select name 
from customer
where referee_id <>2
OR referee_id is null
 ```
