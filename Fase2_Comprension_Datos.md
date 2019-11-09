# FASE 2: COMPRENSIÓN DE LOS DATOS
## Caracterización de la información alfanumérica:
Se crea una base de datos que integra campos tanto del Índice Multidimensional de Condiciones de Vida (IMCV) como de la Inversión en la ciudad. 
Adicionalmente, y para este ejercicio, se ha generado una columna "geográfica" que contiene una serie aleatoria de números entre el 1 y el 16 representando así las comunas de Medellín. 

La base de datos contendrá los siguientes campos: 

INFORMACIÓN DEL PROYECTO:

|IMCV |Inversión municipal|Desagregación Territorial|
|-----|-----|-----|
|Ámbito Estudio|Identificación del sector a analizar|Elaboración propia|Geográfico|x|
|Barrio|Identificación del (los) barrio (s) que impacta(n) el proyecto|DAP|Geográfico|https://geomedellin-m-medellin.opendata.arcgis.com/datasets/barrio-vereda|
|Polígono tratamiento|Identificación de los polígonos de tratamiento urbanos que afectan al proyecto|DAP|Geográfico|https://geomedellin-m-medellin.opendata.arcgis.com/datasets/tratamientos|
|Lotes|Delimitación de los lotes que intervienen en el ámbito de estudio|Catastro|Geográfico|https://geomedellin-m-medellin.opendata.arcgis.com/datasets/lote-del-predio|
|Línea Metrocable|Delimitación del recorrido del metrocable objeto de estudio|DAP|Geográfico|x|
|Estación Metrocable|Ubicación de las estaciones del metrocable objeto de estudio|DAP|Geográfico|x|


