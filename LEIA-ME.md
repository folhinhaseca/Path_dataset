
# 🔬 Previsão de Doenças Relacionadas ao Clima com Machine Learning

Este projeto utiliza técnicas de aprendizado de máquina com Python para prever doenças a partir de condições climáticas e sintomas clínicos. O modelo foi treinado com dados que associam temperatura, umidade, vento e sintomas (como febre, tosse, náusea) à doença diagnosticada.

## 📂 Sobre o dataset

- Variáveis numéricas:  
  `Age`, `Temperature (C)`, `Humidity`, `Wind Speed (km/h)`
- Sintomas (0 ou 1):  
  `fever`, `nausea`, `chills`, `shortness_of_breath`, etc.
- Alvo:  
  `prognosis` (nome da doença)

## 🚀 Pipeline do projeto

1. Importação e visualização dos dados
2. Pré-processamento (separação entre preditores e alvo)
3. Divisão treino/teste
4. Treinamento do modelo (`RandomForestClassifier`)
5. Avaliação (accuracy, precision, recall, F1-score)
6. Interpretação com gráfico de importância das variáveis

## 🧠 Resultados

- Acurácia: 99%
- Excelente desempenho nas métricas de classificação
- As variáveis mais relevantes incluíram sintomas como febre e falta de ar, além de temperatura e umidade

## 📊 Visualização

Um gráfico de barras mostra as variáveis mais importantes na previsão de doenças.

## 🛠️ Tecnologias utilizadas

- Python 3.9+
- Bibliotecas:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

## 📘 Como usar

Clone o repositório e rode o notebook:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
jupyter notebook Projeto_ML_Clima_Doencas.ipynb
```

## 📌 Observações

Este projeto foi desenvolvido com fins educacionais como parte do meu portfólio pessoal.  
Sinta-se à vontade para entrar em contato ou sugerir melhorias!
