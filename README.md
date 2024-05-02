<div id="user-content-toc">
  <ul align="center">
    <summary><h1 style="display: inline-block">Hello World</h1></summary>
  </ul>
</div>


<p>
  Olá! 👋 Meu nome é Adriel, e sou um estudante de aprendizado de máquina do Brasil.
  
  - 🌱 Atualmente, estou focado em estudar Python, mas pretendo expandir para outras linguagens.
</p>


<details>
  <summary>👨‍💻 Mais sobre mim</summary>
  
  - 💬 Tenho 14 anos e moro no Brasil. Sou intermediário em inglês e estou estudando aprendizado de máquina.
</details>


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=AdrielSteteski&hide=contribs,prs_icons=true&theme=transparent)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AdrielSteteski)](https://github.com/anuraghazra/github-readme-stats)
[![Codewars](https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=Codewars&logoColor=white)](https://www.codewars.com/users/AdrielSteteski)
**[![Bitcoin](https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white)](https://github.com/seu_usuario/seu_repositorio)**
import requests

# Função para obter o preço atual do Bitcoin
def get_bitcoin_price():
    response = requests.get("https://api.coingecko.com/api/v3/simple/price?ids=bitcoin&vs_currencies=usd")
    data = response.json()
    return data["bitcoin"]["usd"]

# Obtendo o preço atual do Bitcoin
bitcoin_price = get_bitcoin_price()

# Construindo o URL do badge Shields.io
badge_url = f"https://img.shields.io/badge/Bitcoin-{bitcoin_price}-ff9900?style=for-the-badge&logo=bitcoin&logoColor=white"

print(badge_url)





## 🔥 Habilidades

<div style="flex-basis: 48%;">
  <h3>Linguagens de Programação</h3>
  <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
</div>


<div style="flex-basis: 48%;">
  <h3>Ferramentas e Frameworks</h3>
  <img align="center" alt="VScode" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg">
</div>
