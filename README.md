# 📊 Telecom X – Análise de Cancelamento de Clientes

Este repositório contém um projeto prático de análise de dados voltado para compreender as causas do **alto índice de cancelamento** de clientes da empresa fictícia **Telecom X**, uma operadora de telecomunicações.

---

## 🎯 Objetivo
O principal desafio foi aplicar conceitos de **ETL** (Extração, Transformação e Carga) e **EDA** (Análise Exploratória de Dados) para identificar padrões e características que influenciam a saída dos clientes, ajudando na criação de estratégias para **aumentar a retenção**.

---

## 🛠️ Etapas do Projeto

### 1️⃣ Extração
- 📥 Dados obtidos via API simulada, disponibilizada no GitHub, em formato CSV.

### 2️⃣ Transformação
- 🧹 Limpeza e tratamento dos dados.
- 🔄 Conversão de tipos e padronização de variáveis.
- 🚫 Tratamento de valores ausentes e duplicados.
- ➕ Criação de novas variáveis, como **Contas_Diarias** para estimar faturamento diário.

### 3️⃣ Análise
- 📊 Utilização de **Python, Pandas, NumPy, Seaborn, Matplotlib e Plotly** para gerar visualizações e insights.
- 📉 Avaliação do impacto de variáveis categóricas e numéricas na taxa de cancelamento.

---

## 🔍 Principais Análises Realizadas
-  Distribuição de cancelamento entre clientes ativos e cancelados.
-  Comparação do cancelamento por tipo de contrato.
-  Impacto do tempo de serviço (**tenure**) no cancelamento.
-  Relação entre cancelamento e serviços contratados (internet, telefone, segurança online).
- Análise por forma de pagamento e perfil demográfico.

---

## 💡 Principais Insights
-  **Contratos mensais** apresentam a maior taxa de cancelamento.
-  A maioria dos cancelamentos ocorre nos **primeiros 12 meses** de serviço.
-  Clientes com serviços como **segurança online** e **suporte técnico** tendem a permanecer mais tempo.
- **Métodos de pagamento automáticos** estão associados a menor taxa de cancelamento.
---
## 🖼️ Principais Visualizações

![Distribuição de Cancelamento](imagens/distribuicao_cancelamento.png)  
![Taxa de Cancelamento](imagens/taxa_cancelamento.png)
![Relação entre Cancelamento e Variáveis Numéricas](imagens/Relação%20entre%20Cancelamento%20e%20Var%20Numéricao.jpg)

---
## 🖥️ Tecnologias Utilizadas
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-%233776AB.svg?style=for-the-badge&logo=seaborn&logoColor=white)
![Jupyter](https://img.shields.io/badge/jupyter-%23FA6F1E.svg?style=for-the-badge&logo=jupyter&logoColor=white)
---

## 📂 Arquivos do Projeto
- **[📓 Notebook da Análise](https://drive.google.com/file/d/1Wt9d-KCF9bkSe67l_z40T62rbgK0H91O/view?usp=sharing)** → contém todo o processo de ETL, análise exploratória e geração de gráficos.
- **`dados/`** → pasta com a base de dados utilizada.
- **`imagens/`** → visualizações geradas durante a análise.

---

## 📚 Sobre o Projeto
Este trabalho foi desenvolvido como parte de um estudo prático de análise de dados, com foco em **ETL, análise exploratória e geração de relatórios** para tomada de decisão.

---

##  Autor
**Nome:** Weverton Farias  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wevertonfarias/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Wevertonfarias)


