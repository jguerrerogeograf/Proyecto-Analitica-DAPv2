# FASE 2: COMPRENSIÓN DE LOS DATOS
## Caracterización de la información alfanumérica:
Se crea una base de datos que integra campos tanto del Índice Multidimensional de Condiciones de Vida (IMCV) como de la Inversión en la ciudad. 
Adicionalmente, y para este ejercicio, se ha generado una columna "geográfica" que contiene una serie aleatoria de números entre el 1 y el 16 representando así las comunas de Medellín. 

La base de datos contendrá los siguientes campos: 

INFORMACIÓN DEL PROYECTO:

|BBDD IMCV |BBDD Inversión municipal|BBDD Desagregación Territorial|
|-----|-----|-----|
|Año|Centro Gestor|Comuna|
|DIME|Dependencia||
||Proyecto||
||ID Proyecto||
||Sector||
||Categoría||
||Subcategoría||
||Total Inversión||

Como se ha añadido la desagregación territorial a la base de datos original, se agregará la capa geográfica de las comunas de Medellin para posteriormente unirlas creando la base de datos espacial del proyecto.

|NOMBRE |INFORMACION|FUENTE|FORMATO|DESCARGA INFORMACIÓN|
|-----|-----|-----|-----|-----|
|Comunas|Identificación de las comunas de Medellín|DAP|Geográfico|https://geomedellin-m-medellin.opendata.arcgis.com/datasets/l%C3%ADmite-comuna-corregimiento|
