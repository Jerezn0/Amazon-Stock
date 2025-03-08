# Amazon-Stock
Analisis y visualización de datos

### Descripción del Proyecto:
Este proyecto analiza el comportamiento histórico de los precios de las acciones de Amazon y realiza una predicción utilizando un modelo de regresión lineal. A través de gráficos y métricas, se busca entender la dinámica de los precios de cierre y predecir su valor basado en datos pasados.

### Objetivo del Proyecto:
Visualizar el comportamiento histórico de las acciones de Amazon.

Analizar relaciones clave entre precios de apertura, cierre, máximo, mínimo y volumen.

Predecir el precio de cierre del día siguiente utilizando un modelo de regresión lineal.

### Pasos del Proyecto:
Limpieza y Preparación de Datos

Se eliminaron valores nulos y se convirtió la columna de fechas a formato datetime.

Se creó una nueva columna Lag_1 que contiene el precio de cierre del día anterior para usarla como predictor.

### Análisis Exploratorio de Datos (EDA)
Gráficos lineales para visualizar:
Evolución del precio de cierre a lo largo del tiempo.

Movimientos diarios (apertura, máximo, mínimo, cierre).

Matriz de correlación para identificar relaciones entre variables.

#### Construcción del Modelo
Se utilizó un modelo de Regresión Lineal para predecir el precio de cierre del día actual basado en el precio de cierre del día anterior.
Dividí los datos en conjuntos de entrenamiento y prueba (80%-20%).
#### Evaluación del Modelo
Métricas utilizadas:
Error Cuadrático Medio (MSE): Para medir la precisión de las predicciones.

R-Cuadrado (R²): Para evaluar qué tan bien el modelo explica la variabilidad de los datos.

### Visualizaciones:
Gráficos claros que muestran la evolución de los precios y la relación entre las variables.

Una matriz de correlación para destacar las dependencias clave.

Modelo de Predicción:
El modelo de regresión lineal logró un MSE de X y un R² de Y. (Incluye los valores reales obtenidos).


### Conclusiones
Los precios de cierre tienen una fuerte correlación con el precio del día anterior, lo que valida el uso de una variable rezagada como predictor.
El modelo es sencillo pero efectivo para entender las tendencias generales de los precios.


## Posibles Mejoras:
Implementar modelos más avanzados como ARIMA o redes neuronales recurrentes (RNN) para series temporales.

Analizar más variables, como noticias económicas o indicadores externos.

### Tecnologías Utilizadas
Python
Pandas
Matplotlib
Seaborn
Scikit-learn

#### Herramienta

Jupyter Notebook.

### Conjunto de Datos
Fuente: (Kaggle.com)
