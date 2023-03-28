Data stored in a database can change over time. To address the change in data that is stored in a Dimension table, we came up with a concept "Slowly Changing Dimension" (SCD). There are many types of SCD

- SCD 0
- SCD 1
- SCD 2
- SCD 3

### SCD 0 - Original record remains unchanged
In this type, the data which was inserted in the record when it was created, will stay as-is over its lifetime.

**Example**: A date dimension table. When a day is inserted as "01-01-2023", the information in that record will not change in its lifetime.

![image](./scd0.png)



