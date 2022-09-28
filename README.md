Desenvolvimento de diferentes modelos de Machine Learning de para a competição do Santander pelo Kaggle, utilizando como métricas de erro o MAE (Mean Absolute Error), o RMSE (Root Mean Squared Error), o Coeficiente de Determinação (R-squared) e o valor ajustado para o r-squared. 

<<<<<<< HEAD
Dentro do projeto serão testados 9 modelos de regressão para verificar qual melhor se adapta aos dados. Os modelos são: 
1)Linear Regression
2)Ridge Regression
3)Neural Network Regression
4)Lasso Regression
5)Decision Tree Regression
6)Random Forest
7)KNN Model (K-Nearest Neighbours)
8)SVM Model (Support Vector Machines)
9)Gaussian Regression
=======
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
>>>>>>> 3ccf10e579eb230feaf03048ac6761a63217c464

Também foram testadas 3 técnicas de escalonamento dos dados diferentes: Robust Scaler, Min Max Scaler e StandardScaler. Além disso, foram testados diferentes tamanhos para o conjunto de teste/treino a fim de encontrar a melhor divisão possível.

<<<<<<< HEAD
Após o teste dos modelos sem o tuning de hiperparametros foi utilizado o módulo GridSearchCV para encontrar os melhores parâmetros para o modelo de regressão linear.
=======
Também foi utilizado o módulo GridSearchCV para encontrar os melhores parâmetros para o modelo de regressão linear.
>>>>>>> 3ccf10e579eb230feaf03048ac6761a63217c464
