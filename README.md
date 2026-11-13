# Customer Churn Exploratory Data Analysis (Pandas + Plotly)

*[Leia em Português](#análise-exploratória-de-dados-de-cancelamento-de-clientes-pandas--plotly)*

An Exploratory Data Analysis (EDA) project built with Python, Pandas, and Plotly to diagnose the main drivers of customer churn across a dataset of **50,000 customer records** and simulate the retention impact of targeted business actions.

## Technologies Used

* **Python 3**
* **Pandas** (Data Cleaning, Missing Value Handling & Boolean Filtering)
* **Plotly Express** (Automated Interactive Histograms & Data Visualization)
* **Jupyter Notebook** (Interactive Analysis Environment)

## Project Structure

* `main.ipynb`: Core Jupyter Notebook containing data cleaning, baseline churn calculation, automated visual exploration across all features, and retention scenario simulation.
* `cancelamentos_sample.csv`: Customer dataset sample containing 50,000 records and 12 attributes.
* `requirements.txt`: Project dependencies list.

## Key Insights & Simulation Results

* **Baseline Churn:** **56.79%** churn rate across 49,996 valid customer records.
* **Primary Churn Drivers Identified:**
  * **Monthly Contracts (`duracao_contrato`):** 100% churn rate among monthly subscribers.
  * **Support Friction (`ligacoes_callcenter`):** Nearly 100% churn rate for customers reaching 5 or more support calls.
  * **Payment Delays (`dias_atraso`):** 100% churn rate for customers exceeding 20 days of payment delay.
* **Projected Impact:** Simulating operational fixes for these three bottlenecks reduces the churn rate from **56.8%** to **18.4%** (raising retention from **43.2%** to **81.6%**).

## How to Run

1. Install the dependencies:

    pip install -r requirements.txt

2. Open `main.ipynb` in VS Code or Jupyter Notebook and run all cells.

---

# Análise Exploratória de Dados de Cancelamento de Clientes (Pandas + Plotly)

*[Read in English](#customer-churn-exploratory-data-analysis-pandas--plotly)*

Projeto de Análise Exploratória de Dados (EDA) desenvolvido com Python, Pandas e Plotly para diagnosticar os principais fatores de cancelamento (churn) em uma base de **50.000 registros de clientes** e simular o impacto de ações estratégicas na retenção.

## Tecnologias Utilizadas

* **Python 3**
* **Pandas** (Limpeza de Dados, Tratamento de Valores Nulos e Filtragem Booleana)
* **Plotly Express** (Geração Automatizada de Histogramas Interativos e Visualização de Dados)
* **Jupyter Notebook** (Ambiente Interativo de Análise)

## Estrutura do Projeto

* `main.ipynb`: Notebook principal contendo a higienização da base, cálculo da taxa inicial de churn, análise visual automatizada de todas as variáveis e simulação de cenários de retenção.
* `cancelamentos_sample.csv`: Amostra da base de dados contendo 50.000 registros e 12 atributos.
* `requirements.txt`: Lista de dependências do projeto.

## Principais Insights e Resultados da Simulação

* **Cenário Inicial:** Taxa de cancelamento de **56,79%** sobre 49.996 registros válidos.
* **Principais Causas Identificadas:**
  * **Contratos Mensais (`duracao_contrato`):** 100% dos clientes no plano mensal cancelaram o serviço.
  * **Atrito no Suporte (`ligacoes_callcenter`):** Taxa de cancelamento próxima a 100% a partir da 5ª ligação ao call center.
  * **Atraso no Pagamento (`dias_atraso`):** 100% de cancelamento entre clientes com mais de 20 dias de atraso.
* **Impacto Projetado:** Ao simular ações corretivas para esses três gargalos, a taxa de cancelamento cai de **56,8%** para **18,4%** (elevando a retenção de **43,2%** para **81,6%**).

## Como Executar

1. Instale as dependências:

    pip install -r requirements.txt

2. Abra o arquivo `main.ipynb` no VS Code ou Jupyter Notebook e execute todas as células.
