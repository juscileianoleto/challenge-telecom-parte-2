TelecomX – Previsão de Evasão de Clientes (Churn)
📊 Sobre o Projeto

Este projeto tem como objetivo analisar os fatores que influenciam a evasão de clientes (churn) em uma empresa fictícia de telecomunicações chamada TelecomX.

A evasão de clientes representa um grande desafio para empresas de serviços, pois impacta diretamente na receita e no crescimento do negócio. Por meio de técnicas de Ciência de Dados e Machine Learning, este projeto busca identificar padrões que indiquem quais clientes têm maior probabilidade de cancelar seus serviços.

Com base nessas análises, também são propostas estratégias de retenção de clientes.

🎯 Objetivos

* Identificar os principais fatores que influenciam a evasão de clientes.

* Preparar e tratar os dados para análise.

* Construir modelos de Machine Learning capazes de prever churn.

* Comparar o desempenho dos modelos utilizados.

* Propor estratégias para reduzir a evasão de clientes.

  🗂 Estrutura do Projeto
TelecomX_churn_prediction/
│
├── TelecomX_parte2_prevendo_churn.ipynb
├── README.md
├── dados/
│   └── telecom_churn_dataset.csv
│
└── imagens/

🧹 Pré-processamento dos Dados
Antes da construção dos modelos, foram realizadas etapas importantes de preparação dos dados:

* Remoção de colunas irrelevantes como CustomerID, pois não contribuem para a previsão.

* Tratamento de valores ausentes.

* Conversão de variáveis categóricas em numéricas utilizando One-Hot Encoding.

* Separação dos dados em treino e teste.

* Normalização de algumas variáveis quando necessário.

Essas etapas são fundamentais para melhorar o desempenho dos modelos preditivos.

