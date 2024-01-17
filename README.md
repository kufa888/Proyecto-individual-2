Problema Descriptivo:
Se nos presenta una base de datos que contiene información sobre los incidentes de tráfico en la Ciudad Autónoma de Buenos Aires, Argentina, ocurridos entre 2016 y 2021. El objetivo es analizar estos datos para convertirlos en conocimiento, facilitando la toma de decisiones y la implementación de medidas para reducir los homicidios derivados de estos incidentes.

Funciones de Análisis de Datos:
Se nos encomienda desempeñar el rol de analista de datos, con la tarea de generar KPIs a partir de la información proporcionada. Esto busca crear políticas de rendimiento sobre los incidentes futuros y medir las mejoras obtenidas.

Proceso de ETL:
Durante la extracción inicial de la base de datos, notamos que proviene de un archivo Excel con dos pestañas principales llamadas "Homicidios" y "Víctimas". Cada pestaña contiene un diccionario de datos que describe el significado de las columnas y sus valores. Identificamos valores nulos, eliminamos duplicados y algunas columnas redundantes. También investigamos valores nulos, rescatando información correcta mediante exploración e investigación en páginas oficiales.

Análisis Exploratorio de Datos (EDA):
Con el archivo unificado, procedemos al análisis y exploración de los datos, centrándonos en columnas relevantes con la menor cantidad de valores nulos. Se presentan gráficas sobre la tendencia anual de siniestros, siniestros por comuna, tipo de calle, rol de víctima, vehículo de la víctima y vehículo del acusado. Para detalles adicionales, referirse al archivo EDA.ipynb.

Dashboard:
La implementación del dashboard se realiza con Power BI, alimentándose del archivo generado en el notebook ETL. Se presenta información general sobre la cantidad de siniestros a lo largo del tiempo y la distribución de víctimas mortales por comuna. Se incluyen gráficas interactivas con filtros por año, comuna y edad de las víctimas, abordando siniestros por vehículo de la víctima, vehículo acusado, tipo de calle y rol de la víctima. Se incluyen KPIs como la reducción de homicidios por semestre, a motociclistas y a peatones.

Propuestas y Conclusiones:
Se presentan conclusiones adicionales a las analizadas en los gráficos interactivos. Se proponen campañas de educación vial para peatones y pasajeros, considerando que estos últimos son uno de los principales roles acusados de homicidio. Además, se plantea la propuesta detallada de analizar avenidas y cruces para identificar puntos estratégicos donde implementar medidas como semáforos, reductores de velocidad y señalizaciones.

