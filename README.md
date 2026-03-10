# TelecomX-Latam

# Descripción:
Este proyecto presenta un resumen de los hallazgos clave obtenidos del análisis del dataset de clientes de TelecomX, con un enfoque en la tasa de abandono (Churn) y los factores que la influyen.

# Tecnologías usadas
. Lenguaje: Python 3.12
. Manipulación de datos: Pandas
. Visualización Estadistica: plt.subplot(), plt.pie()
. Entorno: Google Colab

# Analisis
. Resumen de Cargos Financieros y Antigüedad:
  - Los cargos mensuales (Monthly) varían significativamente, indicando diferentes planes de servicio.
  - Los cargos totales (Total) también muestran una amplia dispersión, como era de esperar, influenciados por la antigüedad y los cargos mensuales.
  - La antigüedad (Tenure) promedio es de aproximadamente 32 meses, con clientes que van desde recién incorporados (0 meses) hasta clientes muy antiguos (72 meses).
    
. Distribución de la Tasa de Abandono (Churn):
La visualización del Churn muestra que aproximadamente el 73.5% de los clientes NO abandonan el servicio. Un 26.5% de los clientes SÍ abandonan el servicio.Esta tasa de abandono del 26.5% es significativa y justifica un análisis más profundo para identificar sus causas.

. Abandono por Tipo de Contrato
  El tipo de contrato tiene una influencia notable en la tasa de abandono: Los clientes con contratos 'Month-to-month' (mes a mes) tienen una tasa de abandono considerablemente más alta en comparación con aquellos con contratos de 'One year' (un año) o 'Two year' (dos años). Esto sugiere que los contratos a largo plazo generan una mayor lealtad y retención de clientes.
  
. Antigüedad del Cliente (Tenure) vs. Abandono
El análisis de la antigüedad de los clientes revela una clara tendencia: Los clientes que abandonan (Churn = Yes) tienden a tener una menor antigüedad (picos de densidad en los primeros meses) en comparación con los clientes que NO abandonan (Churn = No), cuya distribución se extiende más hacia periodos de mayor antigüedad.
Esto refuerza la idea de que los clientes más nuevos son más propensos a irse, mientras que la lealtad crece con el tiempo.

# Visualizaciones destacadas
. Grafico de pie con la distribución de churn

. Grafico de barras de abandono por tipo contrato

. Grafico de distribución de antiguedad de clientes


# Como ejecutar el proyecto
Clona este repositorio:
https://github.com/Mayra-25/TelecomX-Latam.git
