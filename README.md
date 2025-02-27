# Classification-algorithms-in-fraud-detection

El objetivo es evaluar el rendimiento de los algoritmos de clasificacion como LogisticRegression, RandomForest y XGBoost en un conjunto de datos de transacciones realizadas por tarjetas de credito [Credit Card Fraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data). El conjunto de datos cuenta con un colectivo de 284 807 transacciones, de las cuales solo el 0.172% son trasacciones fraudalentas 492.

Como se indica en el repositorio de Kaggle, por medidas de confidencialidad se traba con variables que son resultado de un análisis de PCA y por tanto no se cuenta con las características originales de las transacciones. En total se cuenta con 31 variables de las cuales 28 (V1, V2, ... V28) son el resultado de un análisis de PCA, las restantes variables 'Amount' es la cantidad de cada transacción, 'Time', tiempo transacurrido entre cada transacción y 'Class' es la variable respuesta 1 y 0, para caso de fraude y lo contrario, respectivamente. 

