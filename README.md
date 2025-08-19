# 📊 Projeto Telecom X

## 📌 Contexto
A **Telecom X** enfrenta um alto índice de **cancelamentos de clientes (churn)**.  
O objetivo deste projeto é realizar uma **Análise Exploratória de Dados (EDA)** para identificar os principais fatores que influenciam a evasão e gerar insights estratégicos que possam auxiliar na redução do churn.

---

## 🎯 Objetivos do Projeto
- Coletar, tratar e analisar os dados de clientes.  
- Identificar padrões e variáveis que mais impactam a evasão.  
- Gerar visualizações claras para apoiar a tomada de decisão.  
- Preparar a base de dados para etapas futuras de **modelagem preditiva**.

---

## 🗂 Estrutura do Notebook
O notebook está organizado em seções:

1. **Importação e Carregamento dos Dados**  
   - Extração dos dados (JSON/API).  
   - Conversão para DataFrame Pandas.  

2. **Entendimento da Estrutura do Dataset**  
   - Descrição das variáveis.  
   - Tipagem e normalização dos dados.  

3. **Limpeza e Preparação**  
   - Tratamento de valores nulos e inconsistentes.  
   - Conversão de variáveis categóricas e numéricas.  
   - Criação de colunas derivadas (ex.: contas diárias).  

4. **Análise Descritiva**  
   - Estatísticas gerais (média, mediana, desvio padrão, etc.).  

5. **Análise Exploratória de Dados (EDA)**  
   - Distribuição do churn.  
   - Evasão por variáveis categóricas (contrato, gênero, método de pagamento, etc.).  
   - Evasão por variáveis numéricas (cobrança mensal, meses de contrato, etc.).  
   - Correlação entre variáveis e o churn.  

6. **Insights e Conclusão**  
   - Principais padrões identificados.  
   - Recomendações estratégicas para retenção de clientes.  

---

## 🛠 Tecnologias Utilizadas
- **Python 3.x**
- **Pandas** — manipulação e tratamento de dados  
- **NumPy** — operações numéricas  
- **Matplotlib** — visualização de dados  
- **Seaborn** — visualizações estatísticas  

---

## 🔎 Principais Insights
- **Contratos mensais** apresentam a maior taxa de churn.  
- **Métodos de pagamento eletrônicos** estão associados a maior evasão.  
- Clientes com **cobranças mensais mais altas** tendem a cancelar com mais frequência.  
- Quanto **maior o tempo de contrato**, menor a chance de churn.  
- O churn geral gira em torno de **X%** (valor encontrado na base analisada).  

---

## 🚀 Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/telecomx-churn.git

