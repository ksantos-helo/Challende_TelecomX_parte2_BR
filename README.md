# 📊 Análise e Previsão de Evasão de Clientes (Churn)

Projeto de **Machine Learning** para análise e previsão de evasão de clientes (churn) em uma empresa de telecomunicações.

O objetivo do projeto é **identificar padrões de comportamento associados ao cancelamento de clientes** e construir modelos preditivos capazes de estimar a probabilidade de churn.

---

# 📌 Objetivos do Projeto

- 📊 Realizar **Análise Exploratória de Dados (EDA)**
- 🤖 Construir **modelos de Machine Learning para prever churn**
- 🔎 Identificar **variáveis mais importantes para a evasão**
- 📉 Avaliar modelos com métricas de classificação
- 💡 Propor **estratégias de retenção de clientes**

---

# 📂 Estrutura do Projeto


```
customer-churn-ml/
│
├── data/
│ └── telecom_tratado.csv
│
├── notebooks/
│ └── churn_analysis.ipynb
│
├── images/
│ ├── churn_distribution.png
│ ├── correlation_churn.png
│ ├── tenure_vs_churn.png
│ ├── totalcharges_vs_churn.png
│ ├── confusion_matrix_logistic.png
│ ├── confusion_matrix_tree.png
│ ├── logistic_coefficients.png
│ └── tree_feature_importance.png
│
└── README.md
```
---

# 📊 Principais Visualizações

## 📉 Distribuição de Churn

Mostra a proporção de clientes que permaneceram e cancelaram o serviço.

![Distribuição de Churn](images/churn_distribution.png)

---

## 🔎 Correlação das Variáveis com Churn

Identifica quais variáveis possuem maior relação com a evasão de clientes.

![Correlação com Churn](images/correlation_churn.png)

---

## ⏳ Tempo de Permanência vs Churn

Clientes com menor tempo de contrato tendem a apresentar maior taxa de cancelamento.

![Tenure vs Churn](images/tenure_vs_churn.png)

---

## 💰 Total Gasto vs Churn

Clientes que cancelam geralmente apresentam menor gasto acumulado.

![Total Charges vs Churn](images/totalcharges_vs_churn.png)

---

# 🤖 Modelos de Machine Learning

Foram utilizados dois modelos principais:

## 📈 Logistic Regression

Modelo linear utilizado para **classificação binária**, permitindo interpretar a influência de cada variável no churn.

📊 Principais características:

- Necessita normalização das variáveis
- Modelo interpretável
- Bom desempenho em problemas lineares

---

## 🌳 Decision Tree

Modelo baseado em regras que divide os dados em diferentes ramos para classificar clientes.

📊 Principais características:

- Não requer normalização
- Captura relações não lineares
- Fácil interpretação

---

# 📊 Avaliação dos Modelos

Os modelos foram avaliados utilizando métricas clássicas de classificação:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Logistic Regression

![Confusion Matrix Logistic](images/confusion_matrix_logistic.png)

---

## Decision Tree

![Confusion Matrix Tree](images/confusion_matrix_tree.png)

---

# 🔍 Importância das Variáveis

## Logistic Regression Coefficients

Variáveis com maior impacto na previsão de churn.

![Coeficientes Regressão Logística](images/logistic_coefficients.png)

---

## Decision Tree Feature Importance

Importância das variáveis calculada pela árvore de decisão.

![Importância das Variáveis](images/tree_feature_importance.png)

---

# 🚨 Principais Fatores que Influenciam o Churn

A análise identificou alguns fatores críticos para a evasão:

- ⏳ **Baixo tempo de contrato**
- 💰 **Menor gasto total**
- 📉 **Mensalidades mais altas**
- 📄 **Contratos de curto prazo**

Esses fatores indicam que clientes com menor vínculo com a empresa possuem maior probabilidade de cancelamento.

---

# 💡 Estratégias de Retenção

Com base nos resultados obtidos, algumas estratégias podem ajudar a reduzir o churn:

- 🎁 Programas de fidelização
- 📉 Descontos para contratos de longo prazo
- 🎯 Ofertas personalizadas para clientes de risco
- ⭐ Melhoria na experiência do cliente

---

# 🧠 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

---

# 📈 Possíveis Melhorias Futuras

- Implementar modelos mais avançados:
  - Random Forest
  - XGBoost
  - Gradient Boosting

- Aplicar **Cross Validation**
- Otimização de hiperparâmetros
- Construção de **dashboard interativo**

---

# 👨‍💻 Autor

Projeto desenvolvido para estudo de **Machine Learning aplicado à previsão de churn de clientes**.
