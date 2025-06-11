# Expresion-genes-project

## Introducción

Este proyecto tiene como objetivo analizar la expresión génica de un conjunto de muestras utilizando datos de RNA-Seq.
Se emplearán herramientas bioinformáticas para procesar, cuantificar y visualizar la información genética, permitiendo la identificación de genes diferencialmente expresados y su impacto biológico.

## Objetivos

- Procesar y limpiar datos de RNA-Seq 
- Realizar alineación de secuencias contra un genoma de referencia
- Cuantificar la expresión génica
- Identificar genes diferencialmente expresados
- Interpretar resultados mediante análisis funcional 

## Estructura

El proyecto está dividido en varias carpetas

### DOCS

En esta carpeta se guardan los archivos complementarios, presentaciones, esquemas... que son de utilidad para el proyecto.

### DATASETS

En esta carpeta se guardan las bases de datos del proyecto

### SRC

En esta carpeta se guardan los archivos con código que usaremos en el proyecto

## HERRAMIENTAS

- FastQC (Calidad de secuencias)

- Trimmomatic o Cutadapt (Filtración y recorte)

- STAR / HISAT2 (Alineación de RNA-Seq)

FeatureCounts / HTSeq-count (Cuantificación de expresión génica)

DESeq2 / EdgeR (Análisis diferencial)

ggplot2, ComplexHeatmap (Visualización)

