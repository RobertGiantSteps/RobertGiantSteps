### 
# Roberto Martínez Pereira

<h2 align="center">About me</h2>
<h1 align="center">Hi 👋, I'm Robert</h1>
<h3 align="center">Jazz player passionate about programming and web development</h3>

- 🔭 I’m currently working on **Improving all my web knowledge**

- 🌱 I’m currently learning **Python,SQL**

- 👯 I’m looking to collaborate on **any intellectually enriching project**

- 💬 Ask me about **Python,HTML,CSS,SQL**

- 📫 How to reach me **robertjazzsax@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://instagram.com/robertjazzsax" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="robertjazzsax" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://sass-lang.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="40" height="40"/> </a> </p>

```python
def order(operation: tuple, products: dict[str, tuple], money: int) -> int:
    product_code = operation[1]
    ordered_qty = int(operation[2])
    inserted_money = int(operation[3])

    if product_code not in products:
        return money

    stock, price = products[product_code]

    if ordered_qty > stock or ordered_qty * price > inserted_money:
        return money

    change = int(inserted_money) - price * ordered_qty
    money += int(inserted_money) - change
    products[product_code] = (stock - ordered_qty, price)

    return money
```

<h2 align="center">"Controlling complexity is the essence of programming"
--Brian Kernigan 🧠:</h2>


















---


![giphy](https://github.com/RobertGiantSteps/RobertGiantSteps/assets/91851811/319a721f-ad7f-4c57-9deb-1a93a8b17a3e)![giphy-1](https://github.com/RobertGiantSteps/RobertGiantSteps/assets/91851811/c4ae74c3-2753-47f0-b09c-aeae43337563)





---
<!--
**RobertGiantSteps/RobertGiantSteps** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
