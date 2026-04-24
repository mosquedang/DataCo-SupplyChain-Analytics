# DataCo-SupplyChain-Analytics
🚚 DataCo: Supply Chain Intelligence — Fraude y Logística
📋 Descripción del Proyecto
Este proyecto de Data Analytics se centra en la optimización operativa y la seguridad transaccional de una cadena de suministro global. Utilizando un dataset de más de 180,000 registros, se desarrolló un ecosistema de datos en Power BI para identificar cuellos de botella logísticos y patrones críticos de fraude.

El análisis permite a la organización pasar de una postura reactiva a una estrategia proactiva mediante el uso de Inteligencia Artificial y modelado de datos avanzado.

🔍 Key Insights (Hallazgos Críticos)
🛡️ Focalización del Fraude: Se detectó que el 100% de las órdenes etiquetadas como SUSPECTED_FRAUD se concentran exclusivamente en el método de pago TRANSFER (Transferencia Bancaria). Esto permitió proponer una política de seguridad específica para este canal.

📦 Desvío de SLA: El análisis reveló una tasa de 55% de entregas tardías (Late Delivery).

📊 Riesgo por Categoría: Los rubros de "Fishing" y "Water Sports" presentan la mayor incidencia de alertas, sugiriendo la necesidad de validaciones adicionales en estas líneas de producto.

🛠️ Stack Tecnológico
Herramienta de Visualización: Power BI Desktop.

ETL & Limpieza: Power Query (M Language) para la normalización de datos.

Modelado: Esquema de Estrella (Star Schema) con 5 tablas (Hechos, Clientes, Productos, Calendario y Medidas).

Análisis Avanzado: Lenguaje DAX (medidas con variables para optimizar el rendimiento).

IA aplicada: Uso de Influenciadores Clave, Detección de Anomalías y Narrativa Inteligente.

📁 Estructura del Repositorio
Dashboard_DataCo_Final.pbix: Archivo ejecutable con el tablero interactivo de 4 solapas.

Documentacion_Tecnica.pdf: Documento detallado con el Diccionario de Datos, DER y metodología aplicada.

/data: Carpeta con el dataset original utilizado para el análisis.

🚀 Cómo ver el proyecto
Descarga el archivo .pbix.

Ábrelo con Power BI Desktop.

Explora la narrativa desde la Portada hacia el Análisis Operativo.

Proyecto final desarrollado para la certificación de Data Analytics en Coderhouse. Docente: Sole Iójimo.
