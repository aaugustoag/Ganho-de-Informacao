# Ganho-de-Informação
<div align="left"> 
  <img align="center" src="https://img.shields.io/badge/Python-FF8C00?style=for-the-badge&logo=python&logoColor=white"><br>
  <img src="https://img.shields.io/badge/Ciência%20de%20Dados-red">
</div>

Prática de Ganho de Informação no contexto da disciplina Aprendizado de Máquina no CEFET-MG.
## Análise de Atributos para Diferenciar Espécies de Plantas do Gênero Iris
Plantas do gênero Iris possuem diversas espécies que podem ser diferenciadas por algumas características da flor. 

<div align="center">
  <img src="especies.png" alt="Iris">
</div>

Nesta prática, iremos investigar quais atributos distinguem melhor algumas espécies dessa planta. Para isso, usaremos este dataset que possui 150 plantas do gênero Iris com atributos de sua flor (propriedades):

* Tamanho e largura do cálice (em cm);
* Tamanho e largura da pétala (em cm).

<div align="center">
  <img src="partes_flor.png" alt="Partes da Flor">
</div>

##

Existem 3 espécies de plantas do gênero Iris na base que será usada: Iris Setosa, Iris Virginifica e Iris Versicolor.<br>
Nesta atividade, você deverá:

1. Calcular do InfoGain de cada atributo. Armazene o resultado em um DataFrame de duas colunas - nome do atributo e valor de infogain - ordene essa tabela pelo InfoGain;
2. Gerar um gráfico de dispersão (scatter plot) em que o eixo x e y são os dois atributos com InfoGain mais altos e com 3 grupos, cada grupo, uma espécie de flor diferente.

![image](https://github.com/aaugustoag/Ganho-de-Informacao/assets/49174397/52df54db-ae71-4635-a52f-7ea5573348d7)<br>
![image](https://github.com/aaugustoag/Ganho-de-Informacao/assets/49174397/c69b0a83-1b93-4e43-aac4-f157140ee84b)
