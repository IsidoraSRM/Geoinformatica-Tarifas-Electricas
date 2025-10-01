# Sistema de Predicción Geoespacial de Tarifas Eléctricas en Chile

Este repositorio contiene el código, datos y documentación del proyecto del curso de **Geoinformática** (Universidad de Santiago de Chile - USACH, 2° semestre 2025), cuyo objetivo es desarrollar un sistema reproducible para la predicción de tarifas eléctricas integrando técnicas de machine learning y análisis geoespacial con datos del sistema eléctrico nacional.

## Información del Curso

- **Asignatura**: Geoinformática
- **Profesor**: Francisco Parra
- **Institución**: Universidad de Santiago de Chile (USACH)
- **Período**: 2° Semestre 2025

## Integrantes del Proyecto

- Anael Guzmán - [@AnaelGuzman](https://github.com/AnaelGuzman)
- Diego Hernández - [@Diegomuu](https://github.com/Diegomuu)
- Isidora Reveco - [@IsidoraSRM](https://github.com/IsidoraSRM)
- Matías Vejar - [@matiasjava](https://github.com/matiasjava)
- Eliseo Yáñez - [@DevYanezeo](https://github.com/DevYanezeo)

## Descripción del Proyecto

El proyecto busca abordar el desafío de predecir tarifas eléctricas en distintas zonas del país combinando datos satelitales (clima, índices espectrales), información sectorial y modelos espaciales avanzados. Se implementa una arquitectura robusta de tres capas (datos, procesamiento, visualización) y se pone énfasis en reproducibilidad y buenas prácticas.

## Organización del Repositorio

- `README.md`: Documentación principal y guía rápida.
- `requirements.txt` / `environment.yml`: Dependencias y ambiente reproducible.
- `docs/`: Documentación complementaria, informes, presentaciones.
- `data/`:
  - `raw/`: Datos originales o scripts de descarga.
  - `processed/`: Datos ya tratados para análisis.
- `notebooks/`:
  - `01_exploratory.ipynb`
  - `02_preprocessing.ipynb`
  - `03_analysis.ipynb`
- `src/`:
  - `datadownload.py`
  - `preprocessing.py`
  - `visualization.py`
- `outputs/`:
  - `figures/`: Gráficos y estadísticas.
  - `maps/`: Mapas y visualizaciones geoespaciales.

## Reproducibilidad

Toda la organización, código y dependencias están pensados para que cualquier integrante o usuario externo pueda ejecutar los scripts desde cero, descargar los datos e interactuar con los resultados. Se recomienda:

- Revisar y actualizar `requirements.txt` o `environment.yml`
- Ejecutar los notebooks en el orden indicado
- Usar los scripts de descarga/preprocesamiento en `src/`

## Datos

Se emplean fuentes abiertas y públicas:

- Google Earth Engine (MODIS, Sentinel, ERA5)
- Coordinador Eléctrico Nacional (precios, generación, etc.)
- Ministerio de Energía de Chile

## Resultados Esperados

- Mínimo 3 mapas temáticos y 5 gráficos estadísticos
- Visualización interactiva (por ejemplo, con Folium o Streamlit)
- Informe técnico en PDF (LaTeX o Markdown)
- Estructura de carpetas reproducible y alineada a los estándares del curso
