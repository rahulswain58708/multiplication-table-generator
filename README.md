# 🔢 Multiplication Table Generator  

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  
![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)  
![Contributions welcome](https://img.shields.io/badge/Contributions-Welcome-orange)  

A simple Python program that generates the multiplication table of any number entered by the user.  
Perfect for beginners to practice **loops, input handling, and string formatting**.  

---

## 🚀 Features  
- Takes user input  
- Generates multiplication table up to 10  
- Beginner-friendly project  
- Clean and easy-to-understand code  

---

## 🖥️ Code Example  

```python
print('-----------Multiplication Table Generator------------')
num = int(input('Enter a number: '))
for i in range(1, 11):
    print(f"{num} x {i} = {num*i}")
