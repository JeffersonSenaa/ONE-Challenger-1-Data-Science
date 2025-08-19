# 📊 Projeto de Análise de Dados

Este repositório contém uma análise exploratória de dados com o objetivo de analisar faturamentos de lojas, com base em métricas de desempenho como faturamento, satisfação dos clientes e eficiência logística.

## 🧠 Objetivo

Analisar o desempenho das 4 lojas e, por meio de dados e visualizações, recomendar qual delas apresenta **menor eficiência** e, portanto, **é a mais adequada para ser vendida**.

## 🔧 Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab / Jupyter Notebook

## 📌 O que foi analisado?

| Métrica | Descrição |
|--------|------------------------------------------------------------|
| **Faturamento Total** | Soma dos valores de venda da coluna `Preço` |
| **Categorias mais vendidas** | Agrupamento por `Categoria do Produto` |
| **Avaliações dos Clientes** | Média da coluna `Avaliação da compra`  |
| **Produtos mais/menos vendidos** | Contagem de ocorrências na coluna `Produto` |
| **Frete médio** | Média da coluna `Frete` |

## 📈 Gráficos gerados

- Gráfico de **barras** — Faturamento total por loja  
- Gráfico de **pizza** — Distribuição das categorias mais vendidas  
- Gráfico de **dispersão** — Relação entre preço e frete  
- Gráfico de **barras** — Frete médio por loja

## ✅ Conclusão

Com base nas análises realizadas, constatamos que a **Loja 4** apresenta:

- O **menor faturamento total**;
- Uma das **menores médias de avaliação** pelos clientes;
- Baixa expressividade nas vendas dos principais produtos;
- **Frete médio baixo**, possivelmente associado ao menor volume de vendas.

Dessa forma, **a Loja 4 se mostrou a mais adequada para ser vendida**.
