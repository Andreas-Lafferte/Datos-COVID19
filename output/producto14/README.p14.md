# Descripción
Set de 2 archivos que dan cuenta del número de fallecidos por día, según región de residencia, y concatena la historia de los reportes del Ministerio de Salud desde el 22-03-2020.

Se entiende por región de residencia la región que la persona declara como la de su vivienda habitual. 

Nota aclaratoria 1: Los reportes del Ministerio de Salud informan del último día contabilizado para efectos de la elaboración de cada uno de ellos, habitualmente con corte a las 21 hrs.

Nota aclaratoria 2: Los datos son provisorios a la fecha del último reporte, pues se van actualizando retroactivamente a medida que se confirman casos y evoluciona la vigilancia e investigación epidemiológica desarrollada por el Departamento de Epidemiología del Ministerio de Salud del país.

# Fuente
Reporte diario del Ministerio de Salud. Ver en: https://www.gob.cl/coronavirus/cifrasoficiales/#reportes

# Frecuencia de actualización
Actualización diaria.

# Columnas y valores
El primer archivo (FallecidosCumulativo.csv) contiene la columna ‘Región’, seguida por columnas correspondientes a ‘[Fecha]’. Estas últimas columnas, ‘[Fecha]’, indican el número de fallecidos, por región, desde el 22-03-2020 hasta la fecha. El segundo archivo (FallecidosCumulativo_T.csv) contiene la columna ‘Región’, seguida por columnas correspondientes a cada una de las regiones del país, y luego la columna ‘Total’. Las filas corresponden a ‘[Fecha]’, que contienen el número de personas fallecidas por día reportadas en cada región. Estos valores están separados entre sí por comas (csv).
