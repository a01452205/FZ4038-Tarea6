# Actividad Clase Tarea 6 – Continuación Datos Panel

**Econometría Financiera – FZ4038** | EGADE Business School, Tecnológico de Monterrey

**Profesor:** Dr. Raymundo Díaz Robles

**Alumno:** Daniel Mondragón Monroy (A01452205)

**Fecha:** 1 de noviembre de 2026

## Contenido

- **Parte 1. Panel: determinantes del apalancamiento en el sector energético.** Modelo de datos de panel con 5 empresas petroleras de Estados Unidos (XOM, CVX, COP, OXY y DVN) y 28 trimestres (3T 2019 a 2T 2026), con datos de sus estados financieros obtenidos de LSEG. Incluye los modelos agrupado, de efectos fijos y de efectos aleatorios, las pruebas F, de Hausman, de Wooldridge y de Pesaran, y errores estándar de Driscoll-Kraay.
- **Parte 2. Ejercicios del capítulo 16 de Gujarati (16.10 y 16.11).** Modelo log-lineal de costos de aerolíneas (tabla 16.1) y modelos de panel para la producción de huevos (tabla 1.1).

## Archivos

| Archivo | Descripción |
|---|---|
| `Tarea6_A01452205_FZ4038.Rmd` | Código fuente en R Markdown |
| `Tarea6_A01452205_FZ4038.html` | Documento final (descargar y abrir en el navegador) |
| `Tarea6_A01452205_datosLSEG.xlsx` | Datos trimestrales de LSEG de las 5 empresas (Parte 1) |
| `Table16_1.rda` | Datos de costos de aerolíneas, tabla 16.1 de Gujarati (Parte 2) |
| `Table1_1.rda` | Datos de producción de huevos, tabla 1.1 de Gujarati (Parte 2) |
| `gujarati_tabla_1_1.png` | Imagen de la tabla 1.1 del libro |
| `gujarati_tabla_16_2.png` | Imagen de la tabla 16.2 del libro (modelo agrupado) |
| `gujarati_tabla_16_3.png` | Imagen de la tabla 16.3 del libro (modelo de efectos fijos) |
| `logo_egade.png` | Logo de EGADE utilizado en el encabezado |

Los archivos `.rda` provienen del repositorio [brunoruas2/gujarati](https://github.com/brunoruas2/gujarati). En la tabla 1.1 se corrigieron dos errores de captura con los valores del libro, como se explica en el documento.

## Cómo reproducir

1. Descargar todos los archivos en una misma carpeta.
2. Abrir `Tarea6_A01452205_FZ4038.Rmd` en RStudio.
3. Instalar los paquetes `plm`, `lmtest` y `readxl`, si no están instalados.
4. Dar clic en **Knit**.
