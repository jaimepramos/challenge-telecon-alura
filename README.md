# 🚀 Telecom X - Análise de Evasão de Clientes (Churn)

Este projeto faz parte de uma iniciativa estratégica da Telecom X para identificar os fatores que levam ao cancelamento de serviços (Churn). O objetivo é transformar dados brutos em insights acionáveis, permitindo que a equipe de Data Science desenvolva modelos preditivos e estratégias de retenção mais eficazes.

## 📋 Descrição do Desafio

O desafio consiste em realizar o ciclo completo de um projeto de análise de dados:

- **Extração**: Consumo de dados diretamente de uma API em formato JSON
- **Transformação (ETL)**: Tratamento de dados aninhados (nested JSON), limpeza de inconsistências e normalização
- **Análise Exploratória (EDA)**: Identificação de padrões de comportamento e correlações entre variáveis de serviço e a evasão
- **Relatório**: Geração de insights estratégicos para o negócio

## 🛠️ Tecnologias Utilizadas

- Python 3.10+
- **Pandas**: Manipulação e tratamento de dados
- **Requests**: Integração com a API de dados
- **Matplotlib & Seaborn**: Visualizações estratégicas e análise estatística
- **Jupyter Notebook**: Ambiente de desenvolvimento e documentação da análise

## 📖 Dicionário de Dados

| Coluna | Descrição |
|--------|-----------|
| customerID | Número de identificação único de cada cliente |
| Churn | Indica se o cliente deixou a empresa (Sim/Não) |
| gender | Gênero do cliente |
| SeniorCitizen | Cliente com idade igual ou superior a 65 anos |
| tenure | Meses de contrato do cliente |
| Contract | Tipo de contrato (Mensal, Anual, Bienal) |
| InternetService | Tipo de provedor de internet (DSL, Fibra Óptica, Não) |
| Charges.Monthly | Gasto total mensal de todos os serviços |
| Charges.Total | Total acumulado gasto pelo cliente |
| PaymentMethod | Forma de pagamento utilizada |

**Nota**: O dataset completo inclui informações sobre serviços adicionais como OnlineSecurity, TechSupport e StreamingTV.

## 🚀 Como Executar o Projeto

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/TelecomX-Churn-Analysis.git
```

2. Instale as dependências:
```bash
pip install pandas seaborn requests matplotlib
```

3. Execute o notebook principal:
```bash
jupyter notebook notebooks/TelecomX_Analysis.ipynb
```

## 📈 Insights Esperados

Espera-se identificar quais perfis de contrato e tipos de serviço possuem maior correlação com o cancelamento, permitindo intervenções proativas da equipe de CX (Customer Experience).