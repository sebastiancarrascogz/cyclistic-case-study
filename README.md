# Caso de estudio — Cyclistic

Este repositorio contiene un caso de estudio de análisis de datos para comparar el comportamiento de **usuarios casuales** vs **miembros anuales**. El análisis fue realizado en R usando tidyverse, ggplot2 y leaflet, y documentado en R Markdown.

## Ver el reporte
- Abre el archivo **`report.html`** (reporte final renderizado).
- **Nota:** Se recomienda descargar **`report.html`** y abrirlo localmente en el navegador.
- El código fuente del reporte está en **`report.Rmd`**.

## Reproducir el análisis
1. Descarga los datasets (CSV):
   - [Divvy 2019 Q1](https://docs.google.com/spreadsheets/d/1uCTsHlZLm4L7-ueaSLwDg0ut3BP_V4mKDo2IMpaXrk4/template/preview?resourcekey=0-dQAUjAu2UUCsLEQQt20PDA#gid=1797029090)
   - [Divvy 2020 Q1](https://docs.google.com/spreadsheets/d/179QVLO_yu5BJEKFVZShsKag74ZaUYIF6FevLYzs3hRc/template/preview#gid=640449855)

2. Guarda ambos archivos en la carpeta **`data/`** (los nombres esperados son `"Divvy 2019 Q1.csv"` y `"Divvy 2020 Q1.csv"`).

3. Renderiza el reporte ejecutando `report.Rmd` en RStudio (Knit) o con:
   ```r
   rmarkdown::render("report.Rmd")
   ```
## Estructura del repositorio
- `report.Rmd`: análisis reproducible
- `report.html`: reporte final
- `images/`: recursos gráficos
- `data/`: carpeta para datasets (no incluida en el repo)
