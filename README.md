# 🌸 Iris KNN Optimization: EDA & Preprocessing

Este repositório contém uma Análise Exploratória de Dados (EDA) para a aplicação do algoritmo **k-Nearest Neighbors (kNN)**, utilizando o clássico dataset Iris. O projeto foca-se em entender como a distância matemática entre as características morfológicas define a classificação das espécies.

## 📌 Visão Geral do Projeto
O dataset Iris é um marco na estatística e no Machine Learning. Esta análise explora as dimensões de sépalas e pétalas das espécies *Setosa*, *Versicolor* e *Virginica* para:
- Identificar padrões de separabilidade (como o isolamento da *Setosa* via comprimento da pétala).
- Analisar estatísticas descritivas (médias, mínimos e máximos por espécie).
- Detetar *outliers* que possam distorcer cálculos de distância no modelo kNN.

## 🛠️ Tecnologias e Ferramentas
- **Linguagem Principal:** [R](https://www.r-project.org/)
- **Relatório Dinâmico:** [Quarto](https://quarto.org/)
- **Pacotes Utilizados:**
  - `tidyverse`: Manipulação e visualização de dados (`ggplot2`, `dplyr`).
  - `GGally`: Visualização de matrizes de correlação.
  - `knitr`: Formatação de tabelas profissionais.

## 💻 Como Rodar Localmente

### 1. Requisitos
Certifica-te de que tens o **R** e o **Quarto CLI** instalados no teu sistema.

### 2. Configuração do Ambiente
Este projeto utiliza o pacote `renv` para garantir que as versões dos pacotes sejam as mesmas em qualquer máquina. Após clonar o repositório, executa no console do R:

```r
renv::restore()
```
