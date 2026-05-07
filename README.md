# PRÁCTICA DE CALIDAD Y MINERÍA DE DATOS EN PYTHON

Repositorio del proyecto/práctica de **Calidad de Datos y Minería de Datos en Python**.

## Descripción general

En esta práctica se selecciona una base de datos (trabajada en ejercicios anteriores) y se desarrolla un flujo completo que incluye:

1. **Calidad de datos**: perfilado, diagnóstico por dimensiones de calidad y limpieza/mejora de los datos.
2. **Minería de datos**: construcción y evaluación de modelos predictivos, selección del mejor modelo e hiperparametrización.
3. **Despliegue**: puesta en producción del mejor modelo con una interfaz gráfica.

## Objetivos

- Analizar la **calidad de los datos** a partir de un perfilado automático en Python.
- Identificar problemas en distintas **dimensiones de calidad** (p. ej., completitud, consistencia, validez, unicidad, etc.) y proponer mejoras.
- Implementar un proceso reproducible de **limpieza y preparación** de datos.
- Entrenar y comparar modelos predictivos en Python (**Árbol**, **KNN**, **Red neuronal**, **SVM**, **Random Forest**).
- Seleccionar el mejor modelo y realizar **búsqueda de hiperparámetros con GridSearch**.
- Desplegar el modelo final con **interfaz gráfica** y evidenciarlo con un pantallazo.

## Estructura del repositorio (entregables)

> Los nombres/ubicaciones pueden variar según la implementación del equipo. Esta sección describe los entregables requeridos por la rúbrica.

- **Notebook de calidad de datos**
  - Perfilado de datos en Python sobre los datos originales.
  - Diagnóstico de las dimensiones de calidad (en el notebook).
  - Pasos de limpieza y mejora implementados en Python.
  - **Reporte HTML** del perfilado (adjunto en el repositorio).

- **Notebook de aprendizaje / modelo predictivo**
  - Objetivo del modelo (qué se predice y para qué).
  - Configuración y evaluación comparativa de:
    - Árbol de decisión
    - KNN
    - Red neuronal
    - SVM
    - Random Forest
  - Conclusiones sobre la calidad de los modelos.
  - Hiperparametrización del mejor modelo con **GridSearch**.

- **Notebook / proyecto de despliegue**
  - Implementación del despliegue del modelo predictivo con interfaz gráfica.
  - **Pantallazo** del despliegue.

## Proceso (resumen breve)

1. **Carga y exploración inicial** de la base de datos.
2. **Perfilado automático** (reporte HTML) para identificar nulos, outliers, distribuciones, correlaciones, etc.
3. **Diagnóstico de calidad** por dimensiones, con evidencia del perfilado.
4. **Limpieza y transformación**: tratamiento de valores faltantes, formatos, duplicados, outliers y variables.
5. **Modelado predictivo**: partición de datos, entrenamiento y evaluación de múltiples algoritmos.
6. **Selección del mejor modelo** e **hiperparametrización** con GridSearch.
7. **Despliegue** del modelo final en una interfaz gráfica y documentación del resultado.

## Comunicación del proyecto

- El proyecto se entrega en **GitHub** (este repositorio).
- Adicionalmente, se adjuntan a la tarea de Teams:
  - Notebooks solicitados
  - Información adicional requerida
- Se diligencia el **resumen del proyecto** en el archivo compartido de Teams (hasta la columna de visualización de datos, incluyendo Calidad de datos y Minería de datos).

## Créditos / Equipo

- Integrantes: *(agregar nombres del equipo)*
- Curso: *(agregar curso/grupo)*
- Fecha: *(agregar fecha de entrega)*
