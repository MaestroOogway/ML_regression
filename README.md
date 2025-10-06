Taller Práctico I: Regresión con Keras

Este proyecto corresponde a un trabajo de Machine Learning Aplicado donde se implementa un modelo de regresión utilizando el framework Keras. El objetivo principal es predecir el valor de una vivienda en California a partir de variables socioeconómicas, como el ingreso medio del hogar.

---------------------------------Objetivo-------------------------------

Implementar un perceptrón simple (red neuronal densa) con Keras para resolver un problema de regresión.

----------------------------------Dataset---------------------------------------

housing.csv

Contiene datos del censo de California de 1990, incluyendo características de las viviendas y estadísticas demográficas.

-----------------------------Librerías utilizadas---------------------------------------

keras

numpy

pandas

scikit-learn

matplotlib

----------------------------------------Desarrollo-------------------------------------

Importación de librerías y carga de datos.

Preprocesamiento: estandarización de variables y eliminación de outliers.

División del dataset en entrenamiento, validación y prueba.

Construcción del modelo secuencial en Keras con:

Capa de entrada (Dense, input_dim=1).

Capa de salida (Dense(1) con activación lineal).

Entrenamiento del modelo (150 epochs, batch_size=32).

Evaluación con métricas de pérdida y MSE.

Visualización de la pérdida y MSE durante el entrenamiento.

-----------------------------Resultados--------------------------

El modelo logra un MSE bajo, indicando un buen ajuste en la predicción del valor de las viviendas.

Los gráficos muestran una disminución progresiva de la pérdida y del error durante el entrenamiento.

----------------------------Autores--------------------------------


Fabián Vidal

