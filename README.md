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

Factores Clave que Influyen en el Abandono

Contrato:
Los clientes con contratos 'Month-to-month' (mes a mes) tienen la tasa de abandono más alta (42.66%), en contraste con los contratos de 'Two year' (2.84%) y 'One year' (11.66%). Esto indica que los contratos a largo plazo son clave para la retención.

Antigüedad (Tenure):
Existe una clara relación inversa: los clientes con menor antigüedad son mucho más propensos al abandono. La tasa de churn para clientes de 0-1 año es del 46.01%, mientras que para 4-6 años se reduce al 9.22%.

Cargos Mensuales (Monthly Charges):
Los clientes que abandonan (Churn = Yes) pagan en promedio  74.44∗∗almes,significativamentemásquelosquesequedan(‘Churn=No‘),quepagan∗∗ 61.27. Esto sugiere que un mayor costo mensual puede ser un factor de insatisfacción.

Servicios y Métodos de Pago:
Servicio de Internet: Los clientes con Fibra óptica tienen una tasa de abandono del 42.00%, mucho mayor que aquellos con DSL (19.00%) o sin servicio de internet (7.15%). Esto podría indicar problemas con la calidad o el costo del servicio de fibra.

Seguridad en Línea: Los clientes sin el servicio de OnlineSecurity presentan una tasa de abandono del 40.49%.

Método de Pago: El Cheque electrónico (Electronic check) se asocia con la mayor tasa de abandono (45.31%), lo que podría sugerir una falta de lealtad o facilidad para cancelar el servicio para este grupo.


# Visualizaciones destacadas
. Grafico de distribución de tenencia /skewnnes
<img width="566" height="434" alt="image" src="https://github.com/user-attachments/assets/6a66023f-12db-419d-ab20-294488e9c326" />

. Grafico de barras por evasión de tipo de contrato, evasión por metodo de pago, evasión por servicio de internet, evasión por seguridad online

<img width="1606" height="564" alt="image" src="https://github.com/user-attachments/assets/d809e2da-2944-499b-9033-7edb5eb8a5af" />

<img width="1614" height="461" alt="image" src="https://github.com/user-attachments/assets/9ab1edcf-cf15-4901-aa46-f9ad652bfe30" />

. Grafico de proporción de evasión por antiguedad

<img width="1166" height="593" alt="image" src="https://github.com/user-attachments/assets/cea94ec8-ea37-4749-b856-0e987de7ce46" />


# Como ejecutar el proyecto
Clona este repositorio:
https://github.com/Mayra-25/TelecomX-Latam.git
