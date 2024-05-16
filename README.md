Claro, aquí tienes dos `readme.md` para cada uno de los códigos proporcionados:

---

# Clasificación con Árbol de Decisiones

Este script `clasificacion_arbol_decision.py` se centra en la clasificación de un conjunto de datos utilizando un clasificador de árbol de decisiones. A continuación, se proporciona una descripción general de lo que hace el script:

## Funcionamiento del script:

1. **Carga de datos**: El script carga un conjunto de datos CSV llamado `phishdataset.csv` en un DataFrame de Pandas.

2. **Preprocesamiento de datos**: Utiliza Pandas para codificar las características categóricas como variables numéricas utilizando one-hot encoding.

3. **División de datos**: Divide los datos en conjuntos de características (`X`) y etiquetas (`y`) y luego los divide en conjuntos de entrenamiento y prueba.

4. **Entrenamiento del modelo**: Entrena un clasificador de árbol de decisiones utilizando el conjunto de entrenamiento.

5. **Evaluación del modelo**: Realiza predicciones sobre el conjunto de prueba y genera un informe de clasificación que muestra métricas como precisión, recall y F1-score.

---

# Clasificación con SVM (Máquina de Vectores de Soporte)

Este script `clasificacion_svm.py` se enfoca en la clasificación de un conjunto de datos utilizando una Máquina de Vectores de Soporte (SVM) con un kernel lineal. A continuación, se proporciona una descripción general de lo que hace el script:

## Funcionamiento del script:

1. **Carga de datos**: El script carga un conjunto de datos CSV llamado `phishdataset.csv` en un DataFrame de Pandas.

2. **Preprocesamiento de datos**: Utiliza Pandas para codificar las características categóricas como variables numéricas utilizando one-hot encoding.

3. **División de datos**: Divide los datos en conjuntos de características (`X`) y etiquetas (`y`) y luego los divide en conjuntos de entrenamiento y prueba.

4. **Entrenamiento del modelo**: Entrena un clasificador SVM con un kernel lineal utilizando el conjunto de entrenamiento.

5. **Evaluación del modelo**: Realiza predicciones sobre el conjunto de prueba, calcula la precisión del modelo y genera un informe de clasificación que muestra métricas como precisión, recall y F1-score.
