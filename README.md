# classificador de nomes
O código fornecido neste repositório fornece uma implementação simples e direta dos dois algoritmos de classificação **NaiveBayesClassifier e DecisionTreeClassifier**. O código pode ser usado como um ponto de partida para desenvolver aplicações que precisam classificar nomes.

Ponto de partida ideal para estudantes de ML/DS entenderem como funciona o processo de decisão de algoritmos de classificação.

O código fornecido é implementado em Python, usando a biblioteca NLTK. O código é relativamente simples de implementar. Os principais passos são:

Baixar o conjunto de dados de nomes já etiquetados do corpus de nomes do NLTK.

Dividir os dados em dois conjuntos: treinamento e teste.

Extrair as features dos nomes, no caso, a primeira e a última letra.

Treinar o classificador Naive Bayes e o Decision Tree nos dados de treinamento.

Fazer previsões para novos nomes.

<a href="https://colab.research.google.com/github/adsLopess/Lendo-PDF-com-Python/blob/main/leitorPDF.ipynb" target="_blank"><img height="20" alt="Open in Colab" src = "https://colab.research.google.com/assets/colab-badge.svg"></a>

### 🛠 Linguagens & Ferramentas Utilizadas:

<p align="left">  
  <a href="https://www.python.org/" target="_blank"> <img alt="Python" src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white" title="Python" /> </a> 
  <a href="https://colab.google/" target="_blank"> <img alt="Google-Colab" src="https://seekvectors.com/files/download/348b8e2b10e1b01cd8a05a36426d64bf.jpg" title="Colab" height="35" width="50" /> </a>
  <a href="https://www.nltk.org/" target="_blank"> <img alt="Biblioteca NLTK" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAgcAAABhCAMAAAB1TfJnAAAAaVBMVEXOzs4AAADR0dG6urrV1dWLi4vDw8NUVFShoaFmZmaXl5ebm5uDg4MFBQXJycmqqqq/v781NTVKSkp9fX1eXl4XFxcnJyciIiKtra13d3cSEhIwMDBlZWVbW1ttbW2lpaU7OztEREQjIyOptzxMAAADrUlEQVR4nO3c23aiMBSAYYzRHmzRHjzUnuy8/0OOJBsEElzYJst98X83o5XazuIvkDSlKAAAAAAAAAAAAAAAAAAAAAAAAAAAo5mjMa8MbGfOGPOpf/vmkcpqehTdG/PqlTL+rLvRkLls1H7cMP5TV6n+I/gL+zw5+o6EYF+qV+pE7Kx6dtvfzr5Ozni1bqN563HDzP02O44IGtibamesY688jOng7lwHd60O7nodFBu3ybL/YVyF72DyFe6OvB3449Dkngx0kA4my+DwPK6D0eeFbgfSzwsZKFF3sP5dB2a6bOzcBcXD7vQR+eSwA/9uwTUDrqbuIDwzjOqgPWy0i2qThQ0GjkEH9tt9yWcyUKPpILhwH9dBi7l3HYSb9DswU/cFnxJ8+0jk1MG699OZrQNT7t3XmzNi1MN18OjGcG+9K/psx4OnSfudoYHrYD+N7JlcHcgRiIkDVfzxwLh9/t4d2uXpwL65DJg40MV3UNpDMJzP04GMGB/IQBfpwIRnhiwdyIjxgwyUkQ7kt0qH9iA/QweSGxMH6tQdFHbTO15n6MCU6+rhhpGCOk0H8qO6avZRhg6sGzHuSzpQp+lALuRPh+z0HdhPJg60OnVQmG21l2bNOD91B/4ShIkDldod7Nx+qqd7k3fgXu7PWkKHVgeF/ap21E094ZO2gy9//dG+AoEe7Q6Kwl3Oy1Rf4g7e99LBEx0o1OnA+Fkefz2fuIMTzgwKdY8HfrmYPzNk6GC9dP/EVkfjurodFOWj291VCBk62Pl3eQz/DAJX1uvA3rod5h4m72BhZZky88rq9DqQuZ5Pm6GDNzez7B7OCEGZfgdFWZ/CU3cgVx3+gMOcojJBB366Z5/8eFCvSrUf1bMtHegSdCDrxj5stvWJ2+5TaBB2IH+AuszVgUxf3xKCJmEHcmbYZjseyO+bWLauSaSDwv64y/tZpg4KvxiSwaMmsQ7kzHDI1YFZufdnraoisQ7qRcW5OpAzD7fAUCTagSwgy9aBjEm2f/3mkUy8AzlyBx18t/+YuX+bqws6kNkq/u5djXgHMokUdNC+uYHXus3VJR3Ib7gXhKDEQAeFfY91EJqddvslHcjaJwaPWgx1IMvYs3VQmH/VRw8cEHQY6qCe7cnXgQ+NOyTp4BcExBaGmM2vOrgf6CC4JpRLEBYn6eDupxp7wUTupzp8y9RKGb/l6sD9VI9HBO6nqsgl91cevoXy2bfi/soAAAAAAAAAAAAAAAAAAAAAAAAAkMZ/UCso3z1IqccAAAAASUVORK5CYII=" title="NLTK" height="35" width="50" /> </a>
  
