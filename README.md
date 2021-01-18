# SpainAI_2020_reto_NLP

Reto: https://www.spain-ai.com/hackathon2020_reto_NLP.html
Datos: https://www.spain-ai.com/reto_NLP_2020.zip

Demuestra tus habilidades como Data Scientist en el reto de Procesamiento del Lenguaje Natural. En este reto no se pide una simple clasificación, sino la generación del nombre de un producto en base a la descripción del mismo.

# Notas del análisis realizado de los datos

Proviene de un dataset de Zara por los motivos siguientes:
- El conjunto de datos contiene la etiqueta TRF, que era una linea de producto de Zara ahora descontinuada.
- Un miembro del comité organizador trabaja en Zara.
- Se ha realizado búsquedas de descripciones y aparecen en enlaces de Zara

Formato del dataset:
- Unif (LF)
- UTF8

Características de las etiquetas vs descripción:
- El tipo de prenda habitualmente forma parte de la etiqueta del producto.
- Hay palabras en las etiquetas que están ubicadas en el texto, otro conjunto que se puede deducir y otras que no se puede sin la imagen.

Estadisticas significativas del juego de datos:
- Se ha creado un programa denominado data-analysis.py para analizar el juego de datos.
