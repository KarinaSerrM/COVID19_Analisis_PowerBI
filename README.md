# COVID19_Analisis_PowerBI

Este repositorio documenta el desarrollo de un proyecto de análisis de datos sobre COVID-19 utilizando Power BI.

## Objetivo

Visualizar y analizar la evolución de la pandemia a través de métricas clave como contagios diarios, tasas de mortalidad y recuperación, con filtros por país y fecha.

## Proceso realizado

- **Importación y limpieza de datos** en Power Query
  - Importación y combinación de tablas
  - Renombramiento de columnas
  - Desopilación de fechas y casos
  - Reemplazo de valores nulos por cero
  - Corrección de inconsistencias en datos de decesos y recuperados

- **Modelado de datos**
  - Creación de tabla calendario
  - Métricas DAX:
    - Total de muertes
    - Casos diarios
    - Tasa de mortalidad
    - Índice de recuperación

- **Visualizaciones clave**
  - Top 10 países con más contagios y decesos
  - Top 10 países con mayor y menor tasa de mortalidad
  - Top 10 países con mejor índice de recuperación
  - Curva de contagios diarios por país
  - Distribución de casos confirmados, recuperados y fallecidos
 
## Herramientas utilizadas

- **Power BI Desktop**: Para la limpieza, transformación y modelado de datos.
  - **Power Query**: Para la transformación de datos (renombramiento, desopilación, reemplazo de nulos, corrección de inconsistencias).
  - **DAX**: Para la creación de métricas como casos diarios, tasa de mortalidad e índice de recuperación.
- **Power BI Service**: Para la publicación y visualización interactiva en línea.

## Vista del dashboard

Puedes explorar el reporte en Power BI a través del siguiente enlace:

[Ver reporte en Power BI](https://app.powerbi.com/links/pYG-ej7T_X?ctid=a9e17f9e-90be-41d0-84eb-6a48ebe9fec0&pbi_source=linkShare&bookmarkGuid=36dfb0f8-bea6-4925-a4f1-f087eff66f86)

## Conclusiones

Este proyecto permite responder preguntas estratégicas sobre el impacto del COVID-19 en distintos países, facilitando la toma de decisiones informadas y la comunicación visual de hallazgos relevantes.
