# Análisis de la Felicidad Global (2015-2019): Factores y Tendencias
Este código analiza datos de felicidad global a lo largo de varios años (2015-2019) a partir de archivos CSV y realiza un procesamiento para estandarizar y visualizar los datos.
Ayuda a analizar y comparar los niveles de felicidad en diferentes países y años, buscando relaciones con factores como el PIB per cápita, la salud y la percepción de corrupción.

# Paso a Paso del Código
Importación de librerías
Se importa pandas para la manipulación de datos y matplotlib para visualización.

Carga de datos
Se leen los archivos CSV de diferentes años (2015.csv a 2019.csv) en pandas.DataFrame.

Visualización inicial
Se muestran las primeras filas de cada DataFrame y se imprimen los nombres de las columnas para identificar diferencias entre años.

Estandarización de nombres de columnas
Algunos nombres de columnas cambian entre años, por lo que se renombraron para mantener consistencia en los análisis:

Economy (GDP per Capita) → GDP per Capita
Health (Life Expectancy) → Healthy Life Expectancy
Trust (Government Corruption) → Perceptions of Corruption
Family → Social Support
Freedom → Freedom to Make Life Choices
Unificación de los datasets
Se combinan los datos de los distintos años en un único DataFrame para facilitar el análisis.

Análisis exploratorio
Se realizan cálculos estadísticos básicos como promedios, distribuciones y correlaciones entre las variables.

Visualización de datos
Se generan gráficos para identificar patrones y tendencias en la felicidad global a lo largo de los años.
