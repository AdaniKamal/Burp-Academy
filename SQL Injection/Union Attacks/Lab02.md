# Lab 02

## Lab: SQL injection UNION attack, finding a column containing text

**Objective:** Try to find a right column containing text

**Payload:** '+UNION+SELECT+NULL,'sBehYb',NULL--  

**Text:** 'sBehYb'

**Step-by-step:**
1. Intercept filter & Modify the category parameter
2. Find how many column (NULL,NULL,NULL)
3. After get the correct column, replace each NULL until get the correct column.

![737e666ab5294ea2917b5482c3cf0189](https://user-images.githubusercontent.com/44063862/106165777-67edf900-61c6-11eb-8097-2dae05eac776.png)
