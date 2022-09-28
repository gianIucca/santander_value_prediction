Desenvolvimento de diferentes modelos de Machine Learning de para a competição do Santander pelo Kaggle, utilizando como métricas de erro o MAE (Mean Absolute Error), o RMSE (Root Mean Squared Error), o Coeficiente de Determinação (R-squared) e o valor ajustado para o r-squared. <br>

Dentro do projeto serão testados 9 modelos de regressão para verificar qual melhor se adapta aos dados. Os modelos são: <br>
1)Linear Regression<br>
2)Ridge Regression<br>
3)Neural Network Regression<br>
4)Lasso Regression<br>
5)Decision Tree Regression<br>
6)Random Forest<br>
7)KNN Model (K-Nearest Neighbours)<br>
8)SVM Model (Support Vector Machines)<br>
9)Gaussian Regression<br>
<br>
Também foram testadas 3 técnicas de escalonamento dos dados diferentes: Robust Scaler, Min Max Scaler e StandardScaler. Além disso, foram testados diferentes tamanhos para o conjunto de teste/treino a fim de encontrar a melhor divisão possível.<br>

Por se tratar de um conjunto de dados com muitas features diferentes, e sem nenhuma informação sobre essas features, também foi utilizado o método do SelectKBest (https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.SelectKBest.html) para procurar pelas melhores features do modelo. <br>

Após o teste dos modelos sem o tuning de hiperparametros foi utilizado o módulo GridSearchCV para encontrar os melhores parâmetros para os diferentes modelos de regressão linear.

Para concluir o projeto, foi possível verificar que após selecionar a melhor divisão entre treino e teste, escalonar os dados e realizar a otimização dos hiperparametros dos modelos que performaram melhores no conjunto de dados, foi possível chegar em um modelo