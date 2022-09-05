Desenvolvimento de diferentes modelos de Machine Learning de para a competição do Santander pelo Kaggle, utilizando como métricas de erro o MAE (Mean Absolute Error), o RMSE (Root Mean Squared Error), o Coeficiente de Determinação (R-squared) e o valor ajustado para o r-squared. 

Dentro do projeto serão testados 10 modelos de regressão para verificar qual melhor se adapta aos dados. Os modelos são: 
1)Linear Regression <br> 
2)Ridge Regression
3)Neural Network Regression
4)Lasso Regression
5)Decision Tree Regression
6)Random Forest
7)KNN Model (K-Nearest Neighbours)
8)SVM Model (Support Vector Machines)
9)Gaussian Regression
10)Polynomial Regression

O dataset foi separado em treino e teste com a biblioteca train_test_split, sendo testado no código diferentes tamanhos de amostras para verificar o comportamento do modelo.

Também foi utilizado o módulo GridSearchCV para encontrar os melhores parâmetros para o modelo de regressão linear.
