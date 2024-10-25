# Proyecto: Predicción de Acoplamiento Molecular

Este proyecto utiliza **Machine Learning** para analizar y predecir los resultados del acoplamiento molecular, una técnica fundamental en el **diseño de fármacos** y la **biología estructural**. Nuestro objetivo es identificar posibles **inhibidores de proteasas** en un sistema proteína-ligando, mejorando la eficiencia en la predicción de las puntuaciones de acoplamiento molecular.

---

## Descripción

El acoplamiento molecular es una técnica computacional utilizada para predecir la interacción entre una proteína y un ligando, evaluando la afinidad y estabilidad de esta unión mediante una **función de puntuación**. 

Este proyecto busca desarrollar modelos de **aprendizaje automático** que puedan predecir con precisión dichas puntuaciones, reduciendo así el coste computacional de estas simulaciones. Esto permitirá una evaluación más rápida y eficiente de posibles **inhibidores de proteasa**.

---
## Tecnologías Utilizadas

- **Python**: lenguaje de programación principal.
- **Jupyter Notebooks**: plataforma utilizada para el desarrollo y análisis del proyecto.
- **Scikit-learn**: librería para la implementación de algoritmos de Machine Learning.
- **Pandas y Numpy**: para la manipulación y análisis de datos.
- **Matplotlib y Seaborn**: para la visualización de los datos y resultados.

---

## Resultados

Los resultados muestran que nuestros modelos de **Machine Learning** lograron predecir las puntuaciones de acoplamiento molecular con una alta precisión, reduciendo significativamente el coste computacional de las simulaciones tradicionales.

Los modelos evaluados en términos de sus métricas de rendimiento (**MAE, MSE, RMSE, R2**) muestran que tanto  **Random Forest**, **Support Vector Machine (SVM)**, y **Gradient Boosting Machine** son capaces de capturar y predecir patrones en los datos con cierto grado de precisión.

**Random Forest** y **Support Vector Machine (SVM**) muestran un rendimiento bastante similar en términos de R2, con ambos modelos explicando aproximadamente el 60% de la varianza en los datos de salida. Sin embargo, **SVM** exhibe un ligero beneficio con un **MAE** ligeramente inferior y un **MSE** ligeramente superior en comparación con **Random Forest.** Este resultado sugiere que **SVM** tiende a cometer menos errores en términos de la magnitud de las predicciones absolutas.

Por otro lado, **Gradient Boosting Machine** también muestra un rendimiento competitivo, aunque ligeramente inferior en comparación con los otros dos modelos. Aunque aún es capaz de capturar la mayoría de la variabilidad en los datos, los valores ligeramente más altos de **MAE** y **RMSE** indican que las predicciones pueden ser un poco menos precisas en comparación con **Random Forest** y **SVM**.

En resumen, **Support Vector Machine (SVM**) es la opción más viable con un buen equilibrio entre precisión y capacidad predictiva.

![Resultados de Modelos](https://github.com/AndresSepu/Project_molecular/blob/main/Captura%20de%20pantalla%202024-10-24%20161109.png?raw=true)


---

**
