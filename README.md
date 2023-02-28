# Predicción de abandono de clientes

Librerías utilizadas: `Pandas`, `Numpy`, `Matplotlib`, `Seaborn` y `Scikit-Learn`

El presente proyecto predice si un cliente va abandonar o no su banco, dependiendo de ciertas características como su puntaje de crédito, su edad, el balance de la cuenta, si tiene o no tarjeta de crédito y otros parámetros que se encuentran en el dataset `Churn_Modelling.csv`, el cual fue tomado de [Kaggle](https://www.kaggle.com/code/kmalit/bank-customer-churn-prediction/data). La limpieza de los datos se realizó dentro del archivo `limpieza_datos.ipynb`. Para realizar la predicción se utilizaron los siguientes algoritmos, con el fin de evaluar el desempeño de cada uno: regresión logística, máquina de vectores de soporte, arboles de decisión y bosques aleatorios. También se utilizó la optimización paramétrica a través RandomizedSearchCV y GridSearchCV.

Para correr el repositorio de forma local se debe crear un entorno virtual con el siguiente comando:

    Python3 -m venv nombre_entorno_virtual

Se debe activar el entorno virtual e instalar las librerías requeridas a través del archivo requirements.txt

    pip install -r requirements.txt
