\# Proyecto de Análisis de Churn

El análisis de churn detecta y predice por qué los clientes abandonan un 
servicio, usando datos y modelos predictivos. Ayuda a segmentar clientes, entender las causas del 
abandono y crear estrategias para retenerlos, mejorando la satisfacción del cliente y aumentando los ingresos.

\## Parte 3: Implementación Básica de un Modelo de Regresión Logística

Este proyecto tiene como objetivo predecir la probabilidad de churn (deserción) de clientes en un conjunto de datos simple utilizando un modelo de regresión logística.

\### Archivos

- `codigo\_parte3.py`: Contiene el código Python para la implementación básica del modelo de regresión logística.
- `data.csv`: Conjunto de datos utilizado (en este caso, el conjunto de datos se genera dentro del código).

\### Descripción

1. \*\*Creación del conjunto de datos\*\*:
- Se crea un conjunto de datos simple con tres columnas: `tenure`, `monthlycharges` y `churn`.

2\. \*\*División del conjunto de datos\*\*:

- Se divide el conjunto de datos en conjuntos de entrenamiento y prueba.

3\. \*\*Entrenamiento del modelo\*\*:

- Se entrena un modelo de regresión logística con las características seleccionadas.

4\. \*\*Evaluación del modelo\*\*:

- Se evalúa el modelo utilizando la precisión y se muestran las probabilidades predichas.

\### Ejecución

Para ejecutar el código, asegúrate de tener instaladas las siguientes bibliotecas:

- pandas
- scikit-learn

Puedes instalar estas dependencias utilizando `pip`:

\```bash

pip install pandas scikit-learn

