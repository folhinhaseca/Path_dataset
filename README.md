
# 🌍 Weather-Related Disease Forecasting using Machine Learning

This project applies machine learning techniques using Python to predict diseases based on weather conditions and clinical symptoms. The model is trained with data linking temperature, humidity, wind, and symptoms (e.g., fever, cough, nausea) to the diagnosed illness.

## 📂 About the dataset

- Numerical variables:  
  `Age`, `Temperature (C)`, `Humidity`, `Wind Speed (km/h)`
- Binary symptoms:  
  `fever`, `nausea`, `chills`, `shortness_of_breath`, etc.
- Target:  
  `prognosis` (disease name)

## 🚀 Project pipeline

1. Data loading and exploration
2. Preprocessing (feature/target separation)
3. Train-test split
4. Model training (`RandomForestClassifier`)
5. Evaluation (accuracy, precision, recall, F1-score)
6. Feature importance visualization

## 🧠 Results

- Accuracy: 99%
- Outstanding performance on classification metrics
- Most relevant features included symptoms (fever, shortness of breath) and weather factors (temperature, humidity)

## 📊 Visualization

A bar chart shows the most important features for disease prediction.

## 🛠️ Technologies used

- Python 3.9+
- Libraries:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

## 📘 How to use

Clone the repository and run the notebook:

```bash
git clone https://github.com/your-user/repository-name.git
cd repository-name
jupyter notebook Projeto_ML_Clima_Doencas.ipynb
```

## 📌 Notes

This project was developed for educational purposes as part of my personal data science portfolio.  
Feel free to get in touch or suggest improvements!
