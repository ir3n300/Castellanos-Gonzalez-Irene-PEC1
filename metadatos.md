# Metadatos del Dataset de Cáncer Gástrico

## Descripción general

El conjunto de datos contiene información sobre muestras de pacientes con cáncer gástrico, junto con algunos controles. Los datos se recogen mediante análisis NMR (Resonancia Magnética Nuclear).

## Variables

- **SampleID**: Identificador único de cada muestra.
- **SampleType**: Tipo de muestra. Puede ser:
  - **Sample**: Muestra principal.
  - **QC**: Control de calidad.
- **Class**: Clase de la muestra. Las posibles clases son:
  - **BN**: Grupo de muestras benignas.
  - **GC**: Grupo de muestras de cáncer gástrico.
  - **HE**: Grupo de muestras sanas (healthy).
  - **QC**: Control de calidad.

## Datos de los Metabolitos

Los datos contienen 149 variables que corresponden a diferentes metabolitos identificados por NMR. Cada columna tiene el formato M1, M2,... M149, que representan diferentes metabolitos.

## Fuente de los Datos

Este conjunto de datos se generó como parte de un estudio sobre el cáncer gástrico, y fue procesado utilizando herramientas de bioinformática.

