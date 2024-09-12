# Análisis del Dataset del Titanic y Entrenamiento de Modelos

Este repositorio contiene un análisis detallado y el entrenamiento de varios modelos de aprendizaje automático sobre el famoso dataset del Titanic de Kaggle. El objetivo es predecir la supervivencia de los pasajeros en función de diversas características como la clase, edad, tarifa y tamaño de la familia, entre otros.

### Propuesta para Solucionar el Reto
El enfoque principal fue preparar los datos, seleccionar características clave y aplicar varios modelos de clasificación para predecir la probabilidad de supervivencia. Se enfrentaron varios desafíos, como la presencia de datos faltantes, la no linealidad potencial de los datos, y el desbalance de clases. Estos problemas se abordaron mediante la imputación de datos, la normalización y la selección adecuada de características y modelos.

### Problemas Encontrados y Soluciones
- **Datos Faltantes**: Algunas columnas contenían muchos valores faltantes, especialmente en las variables `Cabin` y `Age`. Este problema se resolvió mediante la **imputación** de datos faltantes con la mediana o eliminando características que no aportaban información significativa.
- **No Linealidad de los Datos**: Se consideró que los datos podrían no ser lineales. Para abordar esto, se probaron modelos como **Random Forest** y **K-Nearest Neighbors (KNN)**, que no suponen una relación estrictamente lineal entre las características.
- **Distribución Anormal**: Algunas variables como la tarifa (`Fare`) mostraban una distribución sesgada. Se utilizó la **normalización** de estas características para reducir el impacto de la distribución anormal.

### Características Analizadas:
- `Pclass`: Clase de los pasajeros (1ª, 2ª, 3ª)
- `Age`: Edad de los pasajeros
- `Sex`: Género de los pasajeros
- `SibSp`: Número de hermanos/esposos a bordo
- `Parch`: Número de padres/hijos a bordo
- `Fare`: Tarifa pagada por el billete
- `Embarked`: Puerto de embarque (C = Cherburgo, Q = Queenstown, S = Southampton)

### Modelos Utilizados:
1. **Regresión Logística**: Captura relaciones lineales entre las características y la supervivencia, considerando variables como la edad, tarifa y clase.
2. **K-Nearest Neighbors (KNN)**: Modelo basado en instancias que predice la supervivencia basándose en los pasajeros más cercanos.
3. **Random Forest**: Un método de ensamble que captura interacciones complejas entre características y maneja bien los datos faltantes.
4. **Support Vector Machine (SVM)**: Encuentra fronteras óptimas para clasificar a los sobrevivientes, útil para datos con relaciones no lineales.

### Tareas Principales:
- Preprocesamiento de datos y **ingeniería de características**, como la imputación de valores faltantes y la transformación de datos categóricos.
- **Ajuste de hiperparámetros** utilizando validación cruzada para optimizar cada modelo.
- Evaluación del rendimiento de los modelos usando **accuracy**, matrices de confusión y reportes de clasificación.

### Visualizaciones:
- Análisis exploratorio de los datos (**EDA**) con gráficos para entender la relación entre las características y la supervivencia.
- División de datos y entrenamiento de modelos, ajuste de hiperparámetros en los modelos necesarios.

## LINK COLAB

https://colab.research.google.com/drive/1Ec7SvsvpqWjmN3n6nnp8lMoGY6U_qyVp?usp=sharing
