# Análise da Evolução do Orçamento Público na Paraíba (2014-2023)

![Status](https://img.shields.io/badge/status-concluído-green)

## 📖 Sobre o Projeto

Este repositório contém a análise exploratória de dados sobre a evolução dos gastos e do orçamento público no estado da Paraíba, com foco no período de 2014 a 2023. O projeto foi desenvolvido como requisito para a disciplina de **Pesquisa Aplicada à Ciência de Dados e Inteligência Artificial** do curso de Bacharelado em Ciência de Dados da Universidade Federal da Paraíba (UFPB).

O objetivo principal é entender como os recursos públicos foram distribuídos, identificar as principais áreas de investimento (como saúde, educação e segurança) e analisar o impacto de eventos significativos, como a pandemia de COVID-19, na alocação orçamentária.

## 👥 Autores

* [Hugo Ryan Santos de França Silva](https://github.com/seu-usuario-aqui)
* [Micael Oliveira Lima Toscano](https://github.com/micaeltoscano)
* [Sérgio Cauã dos Santos](https://github.com/seu-usuario-aqui)


## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido inteiramente em Python, utilizando as seguintes bibliotecas para análise e visualização de dados:

* **Python 3**
* **Pandas:** Para manipulação e análise dos dataframes.
* **Matplotlib e Seaborn:** Para a criação dos gráficos e visualizações.
* **Numpy:** Para operações numéricas.
* **Scikit-learn:** Para a aplicação de algoritmos de clusterização (K-Means).
* **Jupyter Notebook:** Como ambiente de desenvolvimento para a análise.

## 📂 Estrutura da Análise

A análise contida no notebook `analise dos dados.ipynb` segue os seguintes passos:

1.  **Importação das Bibliotecas:** Carregamento de todas as ferramentas necessárias.
2.  **Carregamento dos Dados:** Leitura dos datasets do orçamento público.
3.  **Limpeza e Pré-processamento:** Tratamento de valores ausentes, conversão de tipos e formatação dos dados para a análise.
4.  **Análise Exploratória (EDA):**
    * Análise da evolução do valor orçado por ano.
    * Identificação das principais fontes de recursos.
    * Distribuição dos gastos por função (Saúde, Educação, etc.).
    * Comparativo dos orçamentos antes, durante e depois da pandemia.
5.  **Clusterização:** Uso do algoritmo K-Means para agrupar municípios ou órgãos com perfis de gastos semelhantes.
6.  **Visualização de Dados:** Geração de gráficos de barras, linhas e dispersão para ilustrar os insights encontrados.
