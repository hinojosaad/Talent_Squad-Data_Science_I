# Talent_Squad-Data_Science_I

Mi solución al reto propuesto por Talent Squad en la página web https://nuwe.io/challenge/talent-squad-data-science-i.

## Descripción del reto
El reto consiste en construir un modelo predictivo a partir del conjunto de datos _space_X_train.csv_ que contiene las mediciones de los sensores de un cohete espacial. Dichas mediciones son clasificadas en las siguientes categorías de acuerdo al estado del cohete:

* 0 Estable
* 1 Turbulencia Ligera
* 2 Turbulencia Moderada
* 3 Turbulencia Severa
* 4 Turbulencia Extrema

Adicionalente se proporciona el archivo _space_X_test_ el cual contiene mediciones de sensores del mismo cohete pero cuyo estado se desconoce. El objetivo del reto es predecir cuales son los valores en dicho archivo, utilizando como base el _space_X_train_. Adicionalmente se solicita evaluar el desempeño del modelo a través de la métrica __F1_macro__, es decir se considerará que un modelo es mejor si logró hacer una predicción con un __F1_macro__ mayor.


## Archivos del repositorio

* Space_X.ipynb: Notebook describiendo el código en python con el cual se construyó la solución propuesta al reto
* space_X_pred.csv: Archivo que contiene las predicciones del estado del cohete realizadas por el mejor modelo encotrado para los valores contenidos en _space_X_test_


## Modelos utilizados y resultados
