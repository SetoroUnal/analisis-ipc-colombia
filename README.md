# Análisis de Series de Tiempo: IPC Colombia

Documento Bookdown que presenta el análisis del Índice de Precios al Consumidor (IPC) de Colombia mediante técnicas de series de tiempo.

## Contenido

- **Propuesta:** Justificación de la elección del IPC como variable de análisis y descripción de las fuentes de datos (DANE, Banco de la República).
- **Exploración y Patrones:** Visualización de la serie, promedios móviles (MA3, MA6, MA12), funciones de autocorrelación (ACF/PACF), análisis de rezagos y estacionalidad.
- **Descomposición y Estacionariedad:** Descomposición aditiva, multiplicativa y STL; pruebas de estacionariedad (ADF, KPSS); diferenciación ordinaria y estacional; evaluación de transformaciones.
- **Suavizamiento Exponencial y Holt-Winter:** Suavizamiento exponencial simple (SES), método de Holt, método de Holt-Winter (aditivo y multiplicativo), selección automática ETS, evaluación de métricas de error (MAE, RMSE, MAPE) y pronóstico para 2026.

## Datos

Variación mensual del IPC total nacional de Colombia (enero 2010 – diciembre 2025). Fuente: DANE.

## Tecnologías

- R / RStudio
- Bookdown
- Paquetes: forecast, tseries, zoo, ggplot2, lubridate

## Autor

Maestría en Ciencia de Datos - Universidad Javeriana Cali
