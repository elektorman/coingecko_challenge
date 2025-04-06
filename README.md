# Proyecto: coingecko_challenge
## Descripcion
Este proyecto esta elaborado en su totalidad con Noteboolks de Google Colab

## Contenido del proyecto
Este proyecto contiene los siguietes Notebooks:
- 1_CHALLENGE-API
- 2_CHALLENGE_PYSPARK

## Notebook: 1_CHALLENGE-API
- Este notebook se describen cada uno de los pasos realizados para conectar al sitio "coingecko.com" utilizando la API de una cuenta demo
- Para poder utilizar este Notebook, es necesario obtener una API KEY en dicha pagina, ya que la API original no esta incluida en el codigo
- El objetivo es obtener los precios diarios de: Apertura (Open), Precio Maximo (High), Precio Minimo (Low), Precio de cierre (Close) del BITCOIN de un periodo de tiempo dado
- Al ejecutar este Notebook, se obtiene como resultado un archivo CSV con los datos mencionados

## Notebook: 2_CHALLENGE_PYSPARK
- Aqui se describen cada uno de los pasos realizados para obtener las siguientes metricas: Media Movil de 7 dias, Media Movil de 14 dias y Media Movil de 30 dias
- En caso de que la comexion con la API no funcione o no se cuente con la API KEY, se incluye el archivo CSV "btc_challenge.csv" para ejecutar el Notebook.
- Para utilizar el archivo CSV "btc_challenge.csv", simplemente subirlo en la sesion del Notebook en Google Colab
