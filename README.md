# Momento de Retroalimentación Módulo 2
## Portafolio Implementación
Implementación de una técnica de aprendizaje máquina sin el uso de un framework.
### Jorge Chávez Badillo A01749448

### Librerías Utilizadas:

* *matplotlib.pyplot* Utilizada para la creación de gráficos en dos dimensiones. 
* *pandas* Librería para la manipulación y tratamiento de datos. 
* *seaborn* Para la visualización de datos. 
* *sklearn.model_selection.train_test_split* Para la división de un dataset en dos bloques, destinados al entrenamiento y validación del modelo. 
* *numpy* Librería para el cálculo numérico y análisis de datos.
* *sklearn.metrics* Funciones de pérdida, puntiación y utilidad para medir el rendimiento de los modelos de clasificación. 

### Dataset Utilizado

Fish weight analysis and prediction, obtenido de: [dataset](https://www.kaggle.com/code/agustinpugliese/fish-weight-analysis-and-prediction/notebook)

La descripción de cada uno de los atributos del dataset utilizado son los siguientes: 

* *Species* Nombre de la especie del pez. 
* *Weight* Weight of fish in gram g.
* *Length1* Vertical Lentgh in cm. 
* *Length2* Diagonal Lentgh in cm.
* *Length3* Cross Lentgh in cm.
* *Height* Height in cm.
* *Width* Width in cm.

### Métricas de Desempeño 

Para este modelo de regresión líneal se realizaron 3 configuraciones diferentes para el modelo, esto con el propósito de encontrar con qué parámetros se obtiene un score más alto, y que por ende, se lograran mejores resultados en las predicciones, las siguientes figuras muestran las configuraciones de los modelos y sus respectivas métricas. 

**Prueba 1**

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2/blob/main/Imagenes/prediccion1.png" width="500px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2/blob/main/Imagenes/metricas1.png" width="500px">
</p>

**Prueba 2**

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2/blob/main/Imagenes/prediccion2.png" width="500px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2/blob/main/Imagenes/metricas2.png" width="500px">
</p>

**Prueba 3**

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2/blob/main/Imagenes/prediccion3.png" width="500px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2/blob/main/Imagenes/metricas3.png" width="500px">
</p>

Dado que la prueba número 3 arrojó un score más alto por decimales, se decide trabajar bajo ese modelo para el cálculo de la predicción final y su comparación con los valores reales; la figura siguiente muestra tanto los valores de entrada para la predicción, los valores reales, la predicción y las métricas del modelo. 

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2/blob/main/Imagenes/prediccionFinal.png" width="500px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2/blob/main/Imagenes/metricasFinal.png" width="500px">
</p>

<p align = "center">
  <img src="https://github.com/A01749448/momento-retroalimentacion-m2/blob/main/Imagenes/tablaComparativa.png" width="500px">
</p>

### Archivo a Revisar 
                                                                                                                             
Para una mejor visualización del programa y sus resultados, se encuentra el archivo *momentoDeRetroalimentacionM2.ipynb* y de igual forma se encuentra el archivo para correr directamente en un compilador el archivo *momentoDeRetroalimentacionM2.py*
