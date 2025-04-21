
# 🔬 Previsão de Doenças Relacionadas ao Clima com Machine Learning  
# 🌍 Weather-Related Disease Forecasting using Machine Learning

Este projeto utiliza técnicas de aprendizado de máquina com Python para prever doenças a partir de condições climáticas e sintomas clínicos. O modelo foi treinado com dados que associam temperatura, umidade, vento e sintomas (como febre, tosse, náusea) à doença diagnosticada.

This project applies machine learning techniques using Python to predict diseases based on weather conditions and clinical symptoms. The model is trained with data linking temperature, humidity, wind, and symptoms (e.g., fever, cough, nausea) to the diagnosed illness.

---

## 📂 Sobre o dataset | About the dataset

- Variáveis numéricas | Numerical variables:  
  `Age`, `Temperature (C)`, `Humidity`, `Wind Speed (km/h)`
- Sintomas (0 ou 1) | Binary symptoms:  
  `fever`, `nausea`, `chills`, `shortness_of_breath`, etc.
- Alvo | Target:  
  `prognosis` (nome da doença | disease name)

---

## 🚀 Pipeline do projeto | Project pipeline

1. **Importação e visualização dos dados**  
   Data loading and exploration  
2. **Pré-processamento**  
   Separação entre preditores (`X`) e alvo (`y`)  
   Feature/target separation  
3. **Divisão treino/teste**  
   Train-test split  
4. **Treinamento do modelo**  
   Model training (`RandomForestClassifier`)  
5. **Avaliação**  
   Evaluation (accuracy, precision, recall, F1-score)  
6. **Interpretação com gráfico de importância das variáveis**  
   Feature importance visualization

---

## 🧠 Resultados | Results

- **Acurácia / Accuracy:** 99%
- Excelente desempenho nas métricas de classificação  
  Outstanding performance on classification metrics
- As variáveis mais relevantes incluíram sintomas como febre e falta de ar, além de temperatura e umidade  
  Most relevant features included symptoms (fever, shortness of breath) and weather factors (temperature, humidity)

---

## 📊 Visualização | Visualization

Um gráfico de barras mostra as variáveis mais importantes na previsão de doenças.  
A bar chart shows the most important features for disease prediction.

---

## 🛠️ Tecnologias utilizadas | Technologies

- Python 3.9+
- Bibliotecas | Libraries:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

---

## 📘 Como usar | How to use

Clone o repositório e rode o notebook:  
Clone the repository and run the notebook:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
jupyter notebook Projeto_ML_Clima_Doencas.ipynb
```

---

## 📌 Observações | Notes

Este projeto foi desenvolvido com fins educacionais como parte do meu portfólio pessoal.  
This project was developed for educational purposes as part of my personal data science portfolio.

Sinta-se à vontade para entrar em contato ou sugerir melhorias!  
Feel free to get in touch or suggest improvements!
