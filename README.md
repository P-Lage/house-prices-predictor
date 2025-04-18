> 🚀 Projeto de Portfólio • Cientista de Dados em Transição de Carreira (Físico por Formação)

# 🏠 House Prices: Predição de Preços de Imóveis

Este projeto utiliza dados da competição **House Prices - Advanced Regression Techniques** do Kaggle para prever o valor de venda de casas residenciais em Ames, Iowa. A análise foca na construção de um pipeline simples e robusto de regressão, com foco em resolver problemas reais e gerar insights que podem ser reaplicados em diferentes contextos do mercado imobiliário.

---

## 🎯 Objetivo do Projeto
Construir um modelo preditivo capaz de estimar com boa precisão o preço de venda de um imóvel com base em suas características físicas e estruturais.

---

## 🧠 Storytelling e Motivação
A previsão do valor de imóveis é um desafio recorrente em diversas empresas: imobiliárias, bancos, fintechs e seguradoras. Ao aplicar regressão supervisionada, conseguimos estimar preços com base em dados históricos, tornando o processo de precificação mais eficiente, justo e estratégico. Este projeto demonstra como um cientista de dados pode extrair valor prático de um conjunto de dados públicos usando raciocínio lógico, análise de dados e modelagem estatística.

---

## 🔍 Etapas do Projeto

### 1. Análise Exploratória (EDA)
- Estudo da distribuição de `SalePrice`.
- Cálculo de correlações entre variáveis numéricas.
- Identificação de features com forte impacto no preço (ex: `GrLivArea`, `OverallQual`).

### 2. Pré-processamento
- Seleção de variáveis relevantes.
- Tratamento de valores ausentes com mediana.
- Escalonamento com `StandardScaler`.

### 3. Modelagem
- Teste com quatro modelos: `LinearRegression`, `Ridge`, `Lasso` e `RandomForest`.
- Avaliação com RMSE e R².

### 4. Apresentação Final
- Comparação gráfica do desempenho dos modelos.
- Discussão de resultados, limitações e aplicações futuras.

---

## 📊 Resultados Obtidos
Modelos lineares apresentaram bom desempenho com features selecionadas manualmente. O `RandomForestRegressor` teve melhor ajuste, indicando que relações não-lineares são importantes neste tipo de problema.

---

## 🧩 Aprendizados e Reaplicabilidade
- A importância da engenharia de features baseada em análise exploratória.
- Comparar modelos simples e complexos ajuda a entender o trade-off entre interpretabilidade e performance.
- Estratégias usadas aqui podem ser aplicadas em outros contextos de precificação (seguros, automóveis, crédito, etc).

---

## 📁 Estrutura do Projeto
```
├── data
│   ├── raw
│   └── processed
├── notebooks
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_presentation.ipynb
├── src
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   └── modeling.py
├── README.md
```

---

## 📌 Dataset
Disponível em: [Kaggle - House Prices](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

---

## 👨‍🔬 Autor
**Seu Nome Aqui**  
Físico por formação | Estudante de Ciência de Dados  
[LinkedIn](#) | [Email](#)