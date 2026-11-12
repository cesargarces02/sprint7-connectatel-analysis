# Análisis de clientes de ConnectaTel

## Descripción del proyecto
Proyecto final del Sprint 7 de análisis de datos con Python.

El objetivo es analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica, utilizando información histórica hasta 2024 para identificar patrones de consumo, detectar valores atípicos y segmentar clientes.

## Datasets utilizados
- `plans.csv`: características y precios de los planes Básico y Premium.
- `users_latam.csv`: información de 4,000 clientes, incluyendo edad, ciudad, plan y fechas de registro y cancelación.
- `usage.csv`: 40,000 registros de llamadas y mensajes.

## Herramientas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Etapas del análisis
1. Carga y exploración de los tres datasets.
2. Identificación de valores nulos, inválidos y fechas fuera de rango.
3. Limpieza y estandarización de datos.
4. Agrupación de llamadas, mensajes y minutos por usuario.
5. Análisis estadístico y visualización de distribuciones.
6. Detección de valores atípicos mediante boxplots y método IQR.
7. Segmentación de clientes por edad y nivel de uso.
8. Elaboración de conclusiones y recomendaciones comerciales.

## Principales hallazgos
- El grupo de adultos de 30 a 59 años representa aproximadamente el 50% de los clientes.
- Cerca del 73% de los clientes pertenece al segmento de uso medio.
- El 64.875% utiliza el plan Básico y el 35.125% el Premium.
- Se identificaron valores atípicos de consumo que podrían representar oportunidades comerciales.
- Se detectaron y trataron edades inválidas, ciudades desconocidas y fechas de registro fuera del periodo analizado.

## Recomendaciones
- Revisar si los beneficios de los planes Básico y Premium corresponden al consumo real.
- Evaluar ofertas dirigidas a clientes de uso medio y alto.
- Analizar la relación entre segmentos, planes contratados y cancelaciones.
- Fortalecer los controles de calidad de los datos.

## Cómo ejecutar el proyecto
1. Descargar el archivo `.ipynb` de este repositorio.
2. Abrirlo en Jupyter Notebook o Google Colab.
3. Tener disponibles los tres archivos CSV originales.
4. Ajustar las rutas de lectura de los datasets según el entorno.
5. Ejecutar las celdas en orden para reproducir el análisis.

**Nota:** Los datasets originales no están incluidos en este repositorio. Para reproducir los resultados es necesario disponer de ellos.

## Autor
César Garcés

Proyecto de formación en análisis de datos con Python.
