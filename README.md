# 📊 Machine Learning

En este proyecto se utiliza [python](https://www.python.org/) , [Anaconda](https://www.anaconda.com/),y varias librerías para el análisis de datos, todo desarrollado en Jupyter Notebook. Este repositorio contiene ejercicios prácticos enfocados en la aplicación de modelos supervisados para la predicción de productividad en el sector textil. Los ejercicios incluyen el uso de regresión lineal, regresión logística, K-Nearest Neighbors (K-NN), árboles de decisión (CART) y máquinas de vectores de soporte (SVM), proporcionando un enfoque integral para abordar problemas de predicción en este contexto industrial.








## Librerias del Proyecto

- numpy
- pandas
- matplotlib
- seaborn
- scipy
- sklearn
- graphviz
- scikit-learn

## Caracteristicas 

- Predicción de Productividad con SVM
- Modelos Supervisados para Predicción de Productividad Textil - componente practico.




### Predicción de Productividad con SVM

Este notebook se centra en la aplicación de Máquinas de Vectores de Soporte (SVM) para la predicción de productividad.

- Se explica el concepto de SVM y su aplicabilidad en problemas de clasificación y regresión.
- Se implementa el modelo SVM utilizando un conjunto de datos de productividad textil.
- Se ajustan los hiperparámetros del modelo y se evalúa su desempeño mediante técnicas de validación cruzada.
- Se analizan los resultados obtenidos y se discuten las implicaciones de su uso en la industria textil.


## Componente práctico - Regresión logística
### Modelos Supervisados para Predicción de Productividad Textil

Este notebook cubre varios modelos de aprendizaje supervisado aplicados a la predicción de productividad en el sector textil.


1. **Introducción**
   - Se presenta el objetivo del ejercicio, que es aplicar diferentes modelos de machine learning supervisado para predecir la productividad en el sector textil. Se explica brevemente el conjunto de datos utilizado y las características más relevantes.

2. **El componente practico  consiste en:**
   - **Acción 1: Aplicación modelos lineales**
     - En esta sección se implementa la regresión lineal para establecer una relación entre las variables independientes (características del dataset) y la variable dependiente (productividad). Se incluyen pasos como la división del conjunto de datos en entrenamiento y prueba, la estandarización de las variables y la evaluación del modelo utilizando métricas como el R^2 y el error cuadrático medio (MSE).
   
   - **Acción 2: Aplicación modelo logístico**
     - Aquí se utiliza la regresión logística para abordar un problema de clasificación binaria relacionado con la productividad. Se explican los conceptos básicos de la regresión logística, se ajusta el modelo a los datos y se evalúa su desempeño utilizando métricas como la precisión, la matriz de confusión y la curva ROC.
   
   - **Acción 3: Aplicación K-NN**
     - En esta parte, se aplica el algoritmo de K-Nearest Neighbors (K-NN). Se discuten los fundamentos del algoritmo, la selección del valor óptimo de K, y se implementa el modelo para predecir la productividad. La evaluación del modelo incluye métricas como la precisión y el análisis de los resultados obtenidos con diferentes valores de K.
   
   - **Acción 4: Aplicación Árboles de decisión (CART)**
     - Finalmente, se implementa el algoritmo de árboles de decisión, conocido como CART (Classification and Regression Trees). Se describen los principios de los árboles de decisión, se ajusta el modelo a los datos y se analiza su desempeño utilizando métricas como la precisión, el recall y el F1-score. También se visualiza el árbol de decisión para interpretar mejor los resultados.

3. **Conclusiones**
- Se presentan los hallazgos y resultados obtenidos de la aplicación de los diferentes modelos supervisados. Se discuten las ventajas y limitaciones de cada técnica, así como posibles mejoras y consideraciones para futuras aplicaciones.



## Análisis del Proyecto

En este proyecto, se han explorado y aplicado múltiples algoritmos de machine learning supervisado para abordar el problema de predicción de productividad en el sector textil. Cada modelo ha sido implementado y evaluado cuidadosamente para comprender su eficacia y aplicabilidad. A continuación se destacan algunos puntos clave del análisis:

- **Dataset:** El conjunto de datos utilizado contiene diversas características relevantes para la productividad textil. La correcta preprocesación y limpieza de estos datos fue crucial para el éxito de los modelos.
- **Modelos aplicados:** Se aplicaron y compararon varios modelos, incluyendo regresión lineal, regresión logística, K-NN, árboles de decisión y SVM. Cada modelo fue evaluado utilizando métricas adecuadas a su naturaleza, como precisión, recall, F1-score, R^2 y MSE.
- **Evaluación y Validación:** Se utilizaron técnicas de validación cruzada para asegurar la robustez de los modelos. Además, se compararon los resultados para determinar el modelo más efectivo para el problema en cuestión.
- **Visualización:** Se generaron diversas visualizaciones para interpretar y comunicar mejor los resultados, incluyendo gráficos de dispersión, matrices de confusión y árboles de decisión.

## Conclusiones del proyecto

Las principales conclusiones obtenidas de este proyecto son las siguientes:

- **Eficacia de los Modelos:** Cada modelo tiene sus propias ventajas y limitaciones. Por ejemplo, la regresión lineal y logística son fáciles de interpretar, pero pueden no capturar relaciones complejas en los datos. En cambio, los árboles de decisión y SVM pueden modelar relaciones no lineales, aunque pueden ser más difíciles de interpretar.
- **Importancia de la Preprocesación:** La correcta preprocesación de los datos, incluyendo la estandarización y la limpieza, es esencial para el buen desempeño de los modelos de machine learning.
- **Comparación de Resultados:** Los árboles de decisión y el SVM mostraron un desempeño superior en la predicción de productividad, debido a su capacidad para manejar relaciones complejas entre variables. Sin embargo, la simplicidad y la interpretabilidad de los modelos lineales también los hacen valiosos en ciertas aplicaciones.
- **Aplicaciones Futuras:** Los resultados obtenidos en este proyecto pueden ser mejorados con técnicas adicionales como la selección de características, el ajuste de hiperparámetros y el uso de ensambles de modelos. Además, la integración de técnicas de machine learning más avanzadas, como las redes neuronales, podría ofrecer mejoras adicionales.

Este proyecto demuestra cómo las técnicas de machine learning pueden ser aplicadas eficazmente para resolver problemas reales en la industria textil, proporcionando una base sólida para futuras investigaciones y aplicaciones en el campo.

