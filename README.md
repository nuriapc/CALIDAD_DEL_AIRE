# Proyecto de visualización de datos: Calidad del aire en Almassora

Este repositorio contiene el análisis y visualización interactiva de datos de calidad del aire recogidos en el municipio de **Almassora (Castellón)**, los días **25 y 26 de mayo de 2025**, correspondientes a un **domingo (festivo)** y un **lunes (laborable)**.

El objetivo del proyecto es analizar cómo varía la contaminación en diferentes zonas del municipio según:
- El **tipo de día** (festivo o laborable),
- La **franja horaria** (mañana o noche),
- Y el **contaminante** detectado (NO₂, CO₂, O₃, PM2.5 y PM10).

El trabajo forma parte de la segunda parte de la práctica de la asignatura de Visualización de Datos.
---

## Archivos incluidos

- `calidad_aire.Rmd`:  
  Código completo en RMarkdown que incluye limpieza de datos, clasificación por franjas, y preparación de CSVs para visualización.

- `calidad_datos.csv`:  
  Dataset principal con valores registrados por los sensores ambientales, incluyendo: fecha, hora, zona, latitud, longitud y valores para cada contaminante.

- `mapa_no2.csv`:  
  Subconjunto con datos geolocalizados de **NO₂** por zona, usado específicamente para generar una visualización de tipo mapa en Flourish con coordenadas (lat/lon).

---

## Visualizaciones

Las visualizaciones interactivas han sido creadas con Flourish Studio y publicadas como Story. https://public.flourish.studio/story/3155259/ 
Incluyen gráficos comparativos entre zonas y días, con posibilidad de filtrar por franja horaria.

---

## Uso

1. Abrir en RStudio el archivo `calidad_aire.Rmd`
2. Ejecuta el código por bloques o con `Run All`.
3. Los archivos `.csv` generados están listos para ser usados en Flourish u otras herramientas de visualización.

---

## Autora

**Nuria Pesudo Cots**  
Máster en Ciencia de Datos  
Asignatura: Visualización de Datos

---

## Licencia

Este proyecto se publica bajo licencia MIT. Puedes reutilizar, modificar y compartir el contenido atribuyendo la autoría.
