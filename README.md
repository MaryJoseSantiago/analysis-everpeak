# analysis-everpeak

📌 Descripción del proyecto

Este proyecto forma parte del bootcamp de TripleTen y tiene como objetivo analizar la relación entre la movilidad urbana y la productividad económica de las principales ciudades de Latinoamérica.

Para ello se utilizan dos conjuntos de datos reales:

TomTom Traffic Index: información sobre niveles de congestión vehicular.
OECD Cities: indicadores económicos y sociales de distintas ciudades.

A través de un proceso de limpieza, transformación, integración y análisis exploratorio de datos (EDA), se busca identificar si existe una relación entre el tráfico urbano y variables económicas como el PIB per cápita y el desempleo.

🎯 Objetivos
Limpiar y preparar datos provenientes de diferentes fuentes.
Estandarizar nombres de columnas y tipos de datos.
Unir datasets utilizando llaves comunes.
Analizar la relación entre movilidad y productividad económica.
Generar visualizaciones que faciliten la interpretación de los resultados.
Obtener conclusiones que puedan apoyar la toma de decisiones sobre inversiones en infraestructura de transporte.
📂 Dataset utilizados
1. TomTom Traffic Index

Contiene información como:

Ciudad
País
Nivel de congestión
Tiempo promedio de viaje
Fecha de actualización
2. OECD City Economy

Incluye indicadores económicos como:

PIB per cápita
Tasa de desempleo
Población
Otros indicadores socioeconómicos
🛠️ Tecnologías utilizadas
Python 3
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
📊 Metodología

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Carga de datos
Importación de librerías.
Lectura de archivos CSV.
Exploración inicial.
2. Limpieza de datos
Revisión de tipos de datos.
Identificación de valores faltantes.
Renombrado de columnas a formato snake_case.
Corrección de inconsistencias.
3. Preparación
Conversión de variables.
Estandarización de nombres de ciudades y países.
Eliminación de duplicados.
4. Integración
Unión de ambos datasets mediante las columnas compartidas.
5. Análisis Exploratorio (EDA)

Se realizaron análisis para:

Distribución de indicadores económicos.
Distribución de niveles de congestión.
Correlaciones entre variables.
Comparación entre ciudades.
Identificación de tendencias.
6. Conclusiones

Interpretación de los resultados obtenidos y evaluación de la relación entre movilidad urbana y desempeño económico.

📈 Principales habilidades demostradas
Limpieza de datos
Data Wrangling
Manipulación de DataFrames con Pandas
Unión de bases de datos
Análisis exploratorio de datos (EDA)
Visualización de datos
Interpretación de resultados
Documentación de proyectos
