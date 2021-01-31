# Análisis de la actividad taxista por barrios de Nueva York

El dataset utilizado viene bajo el nombre de taxi_2019.csv

Al dataset completo sin transformar se puede acceder mediante el hipervínculo señalado en el pdf

También hemos utilizado el dataset zones.csv para mappear las casi 200 zonas de 
servicio que presentan los taxis a los 5 barrios de la ciudad.

---
## General

El archivo data_transformation.ipynb es el utilizado para transformar los datasets originales en el que hemos utilizado taxi_2019.csv

---
## Elasticsearch/Kibana

Para pasar del .csv al .json para poder subirlo al buscador hemos utilizado el archivo TaxiToJson.py 

El archivo taxi-mapping.json es el utilizado para crear el índice utilizado en el buscador

El archivo Borough_Boundaries.geojson es un archivo utilizado para crear el mapa 
personalizado con las fronteras exactas de los barrios de Nueva York

---
## Hbase

Adjuntamos 3 archivos siguiendo paralelamente los scripts vistos en las clases:

	- Uno para crear la tabla
	- Uno para cargar los datos del .csv a la tabla
	- Uno para eliminar la tabla

---
## Hive

Adjuntamos los archivos para crear y eliminar la tabla además de los archivos utilizados para hacer las queries.

