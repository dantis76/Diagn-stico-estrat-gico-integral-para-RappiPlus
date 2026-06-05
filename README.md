# Eficiencia Operativa y Delivery - Rappi México 🎯📊

## 🎯 Objetivo del Proyecto

Estudio integral desarrollado para analizar y optimizar los cuellos de botella en los tiempos de entrega, patrones de retención de clientes y comportamiento de usuarios en el mercado mexicano. El análisis identifica áreas críticas de mejora operativa mediante la correlación de tiempos de traslado, volumen de pedidos y tasas de Churn.

## 🛠️ Herramientas y Tecnologías

* **Python:** Uso de librerías **Pandas** y **NumPy** para la manipulación avanzada, imputación de nulos y limpieza profunda de datasets.
* **Visualización de Datos:** Creación de un Dashboard Ejecutivo e interactivo utilizando **Power BI** (Modelado en Estrella y DAX).
* **Fuentes de Datos:** Integración y procesamiento de bases de datos internas de logística de delivery, registros de geolocalización y transacciones de usuarios.
* **Documentación:** Desarrollo del flujo ETL en entornos **Jupyter Notebook** / **VS Code** para asegurar la replicabilidad del pipeline.

## 📊 Hallazgos Clave

* **Normalización Geográfica:** Se estandarizaron con éxito los registros inconsistentes de ubicación (variantes de "México", "CDMX", "EdoMex"), logrando una integridad del 100% en el mapeo geoespacial del negocio.
* **Optimización de Tiempos:** La remoción estratégica de *outliers* y la imputación lógica de valores nulos permitieron calcular con total precisión la evolución de los tiempos de entrega sin distorsionar los promedios reales.
* **Impacto:** Se generó un tablero de control automatizado que conecta los scripts de limpieza con Power BI, sirviendo como base estratégica para la toma de decisiones directivas sobre asignación de repartidores y retención de clientes.


