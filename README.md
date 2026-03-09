#**Análisis de Churn de Clientes con Python**
Este proyecto realiza un análisis exploratorio de datos (EDA) profundo sobre un conjunto de datos de telecomunicaciones para identificar los factores clave que impulsan la pérdida de clientes (Churn). Utilizando Pandas para la manipulación y Seaborn/Matplotlib para la visualización, el estudio revela patrones críticos en servicios, demografía y facturación.

##📊 Resumen del Dataset
El dataframe contiene 7,032 registros y 21 columnas, incluyendo:

Target: churn (Si el cliente canceló o no).

Demográficos: Género, ciudadanos senior, socios y dependientes.

Servicios: Telefonía, múltiples líneas, internet (DSL/Fibra), seguridad, backup, etc.

Cuenta: Tipo de contrato, método de pago, cargos mensuales y totales.

##🛠️ Tecnologías Utilizadas
Python 3.x

Pandas: Limpieza y estructuración de datos.

Matplotlib: Estructura base de los gráficos.

Seaborn: Visualizaciones estadísticas avanzadas (Boxplots, Countplots).

##🔍 Hallazgos Principales
1. El Problema de la Fibra Óptica
A pesar de ser un servicio premium, los clientes de Fibra Óptica presentan una tasa de abandono del 42%, comparada con solo el 19% en DSL.

2. Barreras de Salida (Servicios de Valor)
La ausencia de servicios adicionales como Internet Security o Tech Support correlaciona directamente con un churn superior al 40%. Estos servicios actúan como retenedores críticos.

3. Perfil del Cliente en Riesgo
Contratos: Los clientes "Mes a mes" son los más propensos a irse (~42% de churn).

Antigüedad (Tenure): La mayor fuga ocurre en los primeros 10 meses de servicio.

Cargos: Los clientes que cancelan suelen tener cargos mensuales promedio más altos, lo que indica que la empresa pierde a sus usuarios de mayor valor.

##🚀 Cómo ejecutar el Notebook
Sube el archivo .ipynb a Google Colab.

Asegúrate de tener el dataset en la misma ruta o cárgalo usando files.upload().

Ejecuta las celdas de forma secuencial para generar los gráficos analizados.

##💡 Recomendaciones Estratégicas
Implementar planes de lealtad específicos para el segmento Senior.

Migrar a los clientes de "Cheque Electrónico" hacia métodos de pago automáticos.

Revisar la calidad del servicio de Fibra Óptica o ajustar su estrategia de precios.
