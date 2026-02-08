# 🌾 Agricultural Yield Prediction: Machine Learning (India Dataset)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Predictive-Analytics-blue)

[English](#english) • [Português](#portugues)

---

<a name="english"></a>
## 🇺🇸 English

### 📝 Project Overview
This project applies **Data Science** and **Machine Learning** techniques to predict agricultural productivity (Yield) based on environmental, production, and regional factors such as rainfall, fertilizer and pesticide use, area, season, and location. 

Developed using real-world agricultural data from Indian states, this study demonstrates a robust workflow applicable to global agribusiness R&D, focusing on predictive accuracy and model transparency.

### 🔬 Technical Methodology
1. **Data Auditing & EDA:** Initial inspection of ~19,600 records and statistical profiling.
2. **Feature Engineering:** Implementation of One-Hot Encoding for categorical variables (Crop, State, Season).
3. **Modeling:** Training a **Linear Regression** model as a high-interpretability baseline.
4. **Validation:** Performance evaluation using R², MAE, and RMSE metrics.
5. **Interpretability:** Analysis of coefficients to identify the most influential factors on crop yield.

### 📈 Key Results
* **Performance:** The model achieved an **R² ≈ 0.80**, explaining 80% of the yield variability.
* **Strategic Insights:** Identified that specific crops and regional rainfall patterns are the primary drivers of productivity, supporting data-driven decision-making.

---

<a name="portugues"></a>
## 🇧🇷 Português

### 📝 Visão Geral do Projeto
Este projeto aplica técnicas de **Ciência de Dados** e **Machine Learning** para prever a produtividade agrícola (Yield) com base em fatores ambientais e produtivos (chuva, fertilizantes, pesticidas, área e localização).

Desenvolvido com dados reais de estados da Índia, o projeto simula o fluxo de trabalho de departamentos de P&D no agronegócio global, transformando dados brutos em inteligência preditiva para suporte à decisão.

### 🔬 Metodologia Técnica
1. **Auditoria e EDA:** Inspeção inicial de ~19.600 registros e perfil estatístico.
2. **Engenharia de Atributos:** Aplicação de One-Hot Encoding para converter variáveis categóricas (Cultura, Estado, Estação) em modelos numéricos.
3. **Modelagem:** Treinamento de um modelo de **Regressão Linear**, escolhido pela sua alta interpretabilidade técnica.
4. **Validação:** Avaliação de desempenho através das métricas R², MAE e RMSE.
5. **Interpretabilidade:** Análise de coeficientes (Feature Importance) para identificar os fatores de maior impacto no rendimento.

### 📈 Resultados Obtidos
* **Desempenho:** O modelo alcançou um **R² ≈ 0,80**, demonstrando alta aderência aos dados reais.
* **Insights Estratégicos:** Variáveis relacionadas ao tipo de cultura e volume de chuva demonstraram maior peso na produtividade final, permitindo predições seguras para o planejamento de safra.

---

## 📂 Repository Structure / Estrutura do Repositório

- 📄 [crop_yield_analysis.ipynb](./notebooks/crop_yield_analysis.ipynb): Notebook principal com o pipeline de Machine Learning.
- 📊 [crop_yield_india.csv](./crop_yield_india.csv): Dataset original utilizado para treino e teste do modelo.

---
👤 **Author / Autor:** Cleverson Moura Andrade  
*Data Science Intern / Estagiário em Ciência de Dados*
