# Predicción de Efectividad de Tiros en la NBA para el Ex jugador Kobe Bryant

Este repositorio contiene el proyecto final para el curso de **Minería de Datos** de la **Maestría en Ciencias de la Computación**. El desarrollo se rige bajo los principios solicitados de **Ciencia 2.0**, ofreciendo un entorno de código abierto, datos públicos y experimentos 100% reproducibles.

## Estructura del Repositorio
La distribución de archivos es la siguiente:
- `data/kobe_data.csv`: Conjunto de datos histórico extraído de Kaggle.
- `notebook.ipynb`: Artículo corto en formato de Notebook (Google Colab) con los pasos neesarios para la investigación.
- `requirements.txt`: Especificación de las librerías necesarias para el entorno de ejecución.
- `README.md`: Documentación principal del repositorio.

## Ejecución del Experimento
El análisis fue diseñado e implementado para ejecutarse de manera directa y automatizada en la nube:
1. Abra el archivo `notebook.ipynb` o acceda al entorno interactivo de **Google Colab**.
2. Seleccione la opción **Entorno de ejecución > Ejecutar todo** en el menú superior.
3. El código consumirá de forma transparente los datos desde este repositorio y replicará con exactitud las gráficas, métricas y matrices de confusión de los tres modelos evaluados (Regresión Logística, Random Forest y SVM) mediante el control de la semilla aleatoria global (`RANDOM_STATE = 42`).
