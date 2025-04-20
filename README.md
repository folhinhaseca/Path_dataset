# 🔬 Previsão de Doenças Relacionadas ao Clima com Machine Learning

Este projeto utiliza técnicas de **aprendizado de máquina com Python** para prever doenças a partir de condições climáticas e sintomas clínicos. O modelo foi treinado com dados simulados que associam temperatura, umidade, vento e sintomas (como febre, tosse, náusea) à **doença diagnosticada**.

## 📂 Sobre o dataset

O conjunto de dados foi retirado de um arquivo `.csv` contendo:

- Variáveis numéricas: `Age`, `Temperature (C)`, `Humidity`, `Wind Speed (km/h)`
- Variáveis binárias (sintomas): `fever`, `nausea`, `chills`, `shortness_of_breath`, etc.
- Alvo: `prognosis` — representa o diagnóstico clínico (ex: Dengue, Stroke, Influenza, etc.)

## 🚀 Pipeline do projeto

1. **Importação e visualização dos dados**
2. **Pré-processamento**
   - Exclusão de valores ausentes (não houve necessidade no dataset atual)
   - Separação entre variáveis preditoras (`X`) e variável alvo (`y`)
3. **Divisão treino/teste**
4. **Treinamento de modelo**
   - Algoritmo: `RandomForestClassifier`
5. **Avaliação**
   - Métricas de classificação: accuracy, precision, recall, F1-score

## 🧠 Resultados

- **Acurácia:** 99%
- **Classificação eficiente de todas as categorias de doença**
- Excelente desempenho nas métricas macro e micro

## 🛠️ Tecnologias utilizadas

- Python 3.9+
- Bibliotecas:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`

