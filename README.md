# 🌾 Previsão de Produtividade Agrícola com Machine Learning  
### (Dados Agrícolas da Índia)

## 📌 Visão Geral do Projeto
Este projeto aplica técnicas de **Análise de Dados** e **Machine Learning** para prever a **produtividade agrícola (Yield)** com base em fatores ambientais, produtivos e regionais, como volume de chuvas, uso de fertilizantes e pesticidas, área cultivada, estação do ano e localização geográfica.

O estudo foi desenvolvido a partir de **dados agrícolas reais de diferentes estados da Índia**, permitindo a construção e avaliação de modelos preditivos em um contexto agrícola amplo e diverso.  
Apesar do recorte geográfico específico, as **técnicas, métodos e fluxo de trabalho apresentados são amplamente utilizados no agronegócio global**, incluindo empresas multinacionais do setor agrícola.

---

## 📊 Conjunto de Dados
- Fonte: *Agricultural Crop Yield in Indian States Dataset*
- País de referência: **Índia**
- Total de registros: aproximadamente **19.600**
- Cada linha representa dados agrícolas consolidados por:
  - Cultura cultivada
  - Ano da safra
  - Estação agrícola
  - Estado (região da Índia)

### Variáveis disponíveis:
- **Cultura**: tipo de cultura agrícola
- **Ano da safra**
- **Estação**
- **Estado**: estado indiano onde ocorreu o cultivo
- **Área cultivada (hectares)**
- **Produção total**
- **Chuva anual (mm)**
- **Fertilizante utilizado**
- **Pesticida utilizado**

### Variável alvo:
- **Produtividade (Yield)** — produção por unidade de área

Arquivo utilizado no projeto: data/agricultural-yield-india-ml.csv

---

## 🧪 Metodologia Utilizada

O projeto foi desenvolvido seguindo um fluxo típico de **Ciência de Dados aplicado ao agronegócio**, contemplando tanto análises descritivas quanto preditivas:

1. **Carregamento e inspeção inicial dos dados**
2. **Análise exploratória dos dados (EDA)**
3. **Pré-processamento e engenharia de atributos**
   - Renomeação das colunas para português
   - Tratamento de variáveis categóricas
   - Aplicação de One-Hot Encoding
4. **Separação dos dados em conjuntos de treino e teste**
5. **Treinamento de modelo de Machine Learning**
6. **Avaliação do desempenho do modelo**
7. **Análise de interpretabilidade**
   - Importância das variáveis
   - Visualização gráfica dos fatores mais relevantes

---

## 🤖 Modelo de Machine Learning

- Algoritmo utilizado: **Random Forest Regressor**

### Justificativa da escolha:
- Capaz de capturar **relações não lineares**
- Robusto a outliers e variações regionais
- Muito utilizado em aplicações reais no agronegócio
- Permite **interpretação do modelo** por meio da análise de importância das variáveis

---

## 📈 Resultados Obtidos

- O modelo apresentou **bom desempenho preditivo**, com:
  - **R² ≈ 0,80**
- Variáveis relacionadas a:
  - Tipo de cultura
  - Estado
  - Volume de chuva
  - Uso de insumos agrícolas  
  demonstraram forte influência na produtividade.
- A análise de importância das variáveis contribui para:
  - Melhor entendimento do fenômeno agrícola
  - Apoio à tomada de decisões futuras

---

## 📊 Visualizações e Interpretabilidade

Foram gerados gráficos para:
- Identificar as **variáveis com maior impacto na produtividade**
- Facilitar a interpretação do modelo
- Tornar os resultados mais acessíveis para públicos técnicos e não técnicos

Essa abordagem é amplamente utilizada em empresas do setor agrícola para **suporte à decisão baseada em dados**.

---

👤 Autor:
Projeto desenvolvido por Cleverson Moura Andrade
Estágiario em Ciência de Dados
