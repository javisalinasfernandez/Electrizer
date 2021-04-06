# Electrizer
Proyecto en el que, mediante métodos de regresión, se predice el precio de la electricidad en función de la hora, el día de la semana y las condiciones climatológicas. Además también se realiza un análisis en el que se estudian las horas pico y valle que tienen lugar en la factura eléctrica en España.

Los notebooks que componen el proyecto son los siguientes:

**DatosAEMET.ipynb:** Se obtienen los datos meteorológicos a través de la API de la Agencia Española de Meteorología (AEMET). Es necesario obtener una _key_ personal para poder trabajar con la API. Para ello basta con seguir los pasos que se indican en la página: https://opendata.aemet.es/centrodedescargas/inicio

**Electricidad.ipynb:** Se trata del notebook principal. En él se obtienen los datos referentes a la electricidad de Red Eléctrica de España (REE) y se realiza el pretratamiento: limpieza de datos, tratamiento de NaN, imputación, etc. También se realizan aquí los distintos modelos de regresión y se analizan sus resultados, para ver cuál es el mejor modelo.

**Gráficas.ipynb:** Con todos los datos ya recogidos, limpiados y analizados en el notebook anterior se realizan una serie de gráficas para ilustrar de manera gráfica las principales conclusiones

**Mapas.ipynb:** Mapas de España, divididos por provincias, en los que se representan las cuatro variables meteorológicas analizadas durante el proyecto: temperatura, precipitaciones, velocidad del viento y horas de sol.
