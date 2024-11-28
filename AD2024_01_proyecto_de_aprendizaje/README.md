# Análisis Comparativo de Catálogos: Netflix vs. Amazon Prime Video

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar y comparar los catálogos de contenido de dos de las plataformas de streaming más populares: **Netflix** y **Amazon Prime Video**. Utilizando un conjunto de datos con información sobre títulos disponibles en ambas plataformas, se exploran diferentes características del contenido, tales como:

- Géneros más populares
- Distribución de años de lanzamiento
- Directores y actores más relevantes
- Países de producción
- Clasificación por edad
- Duración de películas y series

Se emplean diversas técnicas de análisis y visualización de datos, como **Seaborn**, **Matplotlib**, y **Geopandas**, para obtener una visión profunda de las similitudes y diferencias entre las dos plataformas.

## Objetivos

- Realizar un análisis exploratorio de los datos para entender las principales características de los catálogos de ambas plataformas.
- Comparar las plataformas en términos de géneros, años de lanzamiento, clasificación por edad, actores/actores de reparto, y países de producción.
- Visualizar los resultados de manera clara utilizando gráficos, mapas y diagramas.

## Estructura del Proyecto

El proyecto está estructurado de la siguiente manera:

1. **Carga y Preprocesamiento de los Datos**: Importación y limpieza de los conjuntos de datos de Netflix y Amazon Prime Video, preparación de los datos para su análisis.
2. **Análisis Exploratorio de Datos (EDA)**: Generación de gráficos y estadísticas descriptivas para explorar los diferentes aspectos del catálogo de contenido.
3. **Visualización de Resultados**: Uso de bibliotecas como Seaborn, Matplotlib y Geopandas para visualizar los resultados del análisis.
4. **Conclusiones y Observaciones**: Resumen de los hallazgos clave del análisis comparativo.

## Contenido

El archivo del proyecto está organizado de la siguiente manera:

1. **`notebook.ipynb`**:  
   Este archivo contiene el análisis completo del proyecto. Incluye la carga de datos, preprocesamiento, análisis exploratorio, generación de visualizaciones y la comparación entre los catálogos de Netflix y Amazon Prime Video.

2. **`datasets/`**:  
   Carpeta que contiene los conjuntos de datos utilizados en el proyecto. Aquí encontrarás los archivos de datos de las plataformas de streaming (Netflix y Amazon Prime Video), que incluyen detalles como géneros, años de lanzamiento, clasificación por edad, directores, actores, y más.

3. **`images/`**:  
   Carpeta con los logotipos de las plataformas de streaming, que se utilizan en el encabezado del notebook.

4. **`requirements.txt`**:  
   Este archivo enumera las librerías necesarias para ejecutar el proyecto, junto con sus versiones específicas.

## Requisitos

Para ejecutar este proyecto de manera efectiva, se deben instalar las siguientes librerías de Python:

- contextily==1.6.2
- geopandas== 1.0.1
- matplotlib==3.9.2
- numpy==1.26.4
- pandas==2.2.2
- plotly==5.24.1
- seaborn==0.13.2
- wordcloud==1.9.4

Puedes instalar todas las dependencias utilizando el siguiente comando:

```bash
pip install -r requirements.txt
