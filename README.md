Desenvolvimento de diferentes modelos de Machine Learning de para a competição do Santander pelo Kaggle, utilizando como métricas de erro o MAE (Mean Absolute Error), o RMSE (Root Mean Squared Error), o Coeficiente de Determinação (R-squared) e o valor ajustado para o r-squared. 

Dentro do projeto serão testados 10 modelos de regressão para verificar qual melhor se adapta aos dados. Os modelos são: <br>
1)Linear Regression   <br> 
2)Ridge Regression  <br>
3)Neural Network Regression <br>
4)Lasso Regression  <br>
5)Decision Tree Regression  <br>
6)Random Forest <br>
7)KNN Model (K-Nearest Neighbours)  <br>
8)SVM Model (Support Vector Machines) <br>
9)Gaussian Regression <br>
10)Polynomial Regression  <br>

O dataset foi separado em treino e teste com a biblioteca train_test_split, sendo testado no código diferentes tamanhos de amostras para verificar o comportamento do modelo.

Também foi utilizado o módulo GridSearchCV para encontrar os melhores parâmetros para o modelo de regressão linear.
