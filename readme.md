# Predição de Customer Churn
Este projeto utiliza uma série de métodos de machine learning para a predição de churn, comparando seus resultados.

### Datasets

Dois Datasets foram utilizados no projeto:
- Telecom Customer Churn Prediction
https://github.com/YBIFoundation/Dataset/raw/main/TelecomCustomerChurn.csv
- Churn Modelling
https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling/data

### Técnicas e Algorítmos

Para cada dataset foram aplicados os seguintes modelos:
- Random Forest
- Logistic Regression
- Support Vector Machines
- Gradient Boosting
- K Nearest Neighbor

### Avaliação de Resultados
Como critério de comparaçào de resultados foram calculadas a Matriz de Confusão e Acurácia da classificação.

### Resultados

#### Banking Churn Prediction - Accuracy sem Feature Engineering

| Random Forest | Logistic Regression | Support Vector Machines | Gradient Boosting | KNN |
|---|---|---|---|---|
| 0.8675 | 0.7833 | 0.7938 | 0.7896 | 0.7704

<img src=images/banking_accuracy_comparison.png>

#### Telecom Churn Prediction - Accuracy com Feature Engineering

| Random Forest | Logistic Regression | Support Vector Machines | Gradient Boosting | KNN |
|---|---|---|---|---|
| 0.7796 | 0.7839 | 0.7938 | 0.7704 | 0.7896

<img src=images/telecom_accuracy_comparison.png>
