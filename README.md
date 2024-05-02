### Hi there 👋
[![Python](https://img.shields.io/badge/Python-Developer-blue)](https://github.com/AdrielSteteski)

import matplotlib.pyplot as plt

# Dados do gráfico de exemplo
categorias = ['Categoria 1', 'Categoria 2', 'Categoria 3', 'Categoria 4']
valores = [10, 20, 15, 25]

# Criando o gráfico de barras
plt.bar(categorias, valores, color='skyblue')
plt.xlabel('Categorias')
plt.ylabel('Valores')
plt.title('Meu Gráfico Personalizado')

# Salvando o gráfico como imagem
plt.savefig('grafico.png')

# Gerando o conteúdo do README.md com o gráfico incorporado
readme_content = """# Meu Projeto Incrível

Bem-vindo ao meu projeto incrível! Este é um lugar onde eu compartilho meu trabalho em desenvolvimento web BackEnd usando Python.

## Gráfico Personalizado

![Gráfico](grafico.png)

## Visão Geral

Este projeto é uma demonstração do meu aprendizado e habilidades em desenvolvimento web BackEnd.

...

"""

# Escrevendo o conteúdo no arquivo README.md
with open("README.md", "w") as readme_file:
    readme_file.write(readme_content)
