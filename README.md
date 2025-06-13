
# 📊 Análisis de Llamadas de Emergencia 911 (CDMX 2021-2022)

Este repositorio contiene un proyecto de análisis de datos basado en los registros de llamadas al número de emergencias **911** de la Ciudad de México, correspondientes al primer y segundo semestre de 2021 y al primer semestre de 2022.

Los análisis exploran patrones temporales, distribución por alcaldía y tipo de incidente, con énfasis en detectar tendencias, categorías frecuentes y posibles anomalías.

## 📁 Estructura del Repositorio

- `Llamadas911.Rmd` – Documento principal en R Markdown con todo el análisis.
- `archivo_combinado.csv` – Base de datos combinada y preprocesada.
- `imagenes/` – Carpeta (opcional) para almacenar gráficos o resultados.
- `README.md` – Este documento.

## 🔧 Requisitos

Antes de ejecutar el proyecto, asegúrate de tener instalado en R los siguientes paquetes:

```r
install.packages(c("tidyverse", "lubridate", "DT", "readr", "viridis", "knitr"))
```

## ▶️ Cómo reproducir el análisis

1. Abre el archivo `Llamadas911.Rmd` en RStudio.
2. Verifica que el archivo `archivo_combinado.csv` esté en el mismo directorio.(ver sección de datos para bajarlos de ahí y crear la base).
3. Haz clic en el botón **"Knit"** para generar el documento en HTML con los gráficos, tablas y análisis incluidos.

## 📈 Contenidos del Análisis

1. Promedio mensual de incidentes por categoría
2. Análisis por alcaldía y por semestre
3. Detección de los incidentes más frecuentes
4. Distribución horaria de llamadas por tipo de emergencia
5. Análisis de falsas alarmas

## 📌 Datos

Los datos fueron obtenidos del [Portal de Datos Abiertos de la Ciudad de México](https://datos.cdmx.gob.mx), específicamente del conjunto de datos sobre llamadas al número de emergencias 911.

## 📄 Licencia

Este proyecto se comparte bajo la licencia [MIT](LICENSE), salvo los datos originales, que pertenecen a la Agencia Digital de Innovación Pública del Gobierno de la Ciudad de México.
