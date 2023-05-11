### Hi there 👋
# Roberto Martínez Pereira

<h2 align="center">About me</h2>

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



<h2 align="center">My stack :man_technologist:</h2>

<p align="center">Tools that I use on a daily basis, or that I've used or worked (either much or a bit) with on the past</p>
<p align="center">
  <a href="https://stackshare.io/anhello/my-personal-stack">
    <img src="http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat" alt="AnhellO :: StackShare" />
  </a>
</p>

<h2 align="center">Github stats :bar_chart:</h2>

<h4 align="center">Visitor's count :eyes:</h4>

<p align="center"><img src="https://profile-counter.glitch.me/{RobertGiantSteps}/count.svg" alt="AnhellO :: Visitor's Count" /></p>

<h4 align="center">Top langs :tongue:</h4>

<p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AnhellO&langs_count=10&theme=tokyonight&layout=compact" alt="AnhellO :: Top Langs" /></p>

<h4 align="center">Profile stats :musical_keyboard:</h4>



<p align="center"><img src="https://thumbs.gfycat.com/PeriodicGlisteningCapeghostfrog.webp" alt="Synthwave" height="400" width="500"></p>


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
