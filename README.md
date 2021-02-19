# Projeto-1-Classificadores-SIN-460

Projeto proposto pela professora Larissa Rodrigues na disciplina de Mineração de Dados(SIN460), da UFV-CRP

Foram comparados dois metodos de classificação (Naive Bayes Gaussian e Decision Tree).
O objetivo era encontrar o melhor classificador e analisar as vantagens e desvantagens de cada um.

**Dataset 1:**
Red Wine Quality - diponível em: https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009

**Resultados obtidos:**

| Classificador | Acurácia | f1-score |
| :--- | :---: | :---: |
| NB Gaussian | 0.8525 | 0.85 |
| Decision Tree | 0.8975 | 0.90 |

Area da curva ROC: 
| Classificador | Area |
| :--- | :---: |
| NB Gaussian | 0.865 |
| Decision Tree | 0.805 |



**Dataset 2:**
Pima Indians Diabetes Database - diponível em: https://www.kaggle.com/uciml/pima-indians-diabetes-database

**Resultados obtidos:**

| Classificador | Acurácia | f1-score |
| :--- | :---: | :---: |
| NB Gaussian | 0.7403 | 0.74 |
| Decision Tree | 0.6970 | 0.70 |


Area da curva ROC: 
| Classificador | Area |
| :--- | :---: |
| NB Gaussian | 0.801 |
| Decision Tree | 0.676 |


**Dataset 3:**
Mushroom Classification - diponível em: https://www.kaggle.com/uciml/mushroom-classification

**Resultados obtidos:**

| Classificador | Acurácia | f1-score |
| :--- | :---: | :---: |
| NB Gaussian | 0.9266 | 0.93 |
| Decision Tree | 1.0 | 1.00 |


Area da curva ROC: 
| Classificador | Area |
| :--- | :---: |
| NB Gaussian | 0.956 |
| Decision Tree | 1.0 |


Alem dos dados de classificação tradicionais, também foram implementadas curvas ROC para a comparação ainda mais profunda dos classificadores.
 
