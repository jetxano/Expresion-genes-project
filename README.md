# Expresion-genes-project

## INTRODUCCIÓN

Este proyecto tiene como objetivo **analizar la expresión génica de un conjunto de muestras utilizando datos de *RNA-Seq***.

Se emplearán herramientas bioinformáticas para procesar, cuantificar y visualizar la información genética, permitiendo la identificación de genes diferencialmente expresados y su impacto biológico.

## OBJETIVOS

- Procesar y limpiar datos de *RNA-Seq*.
- Realizar alineación de secuencias contra un genoma de referencia.
- Cuantificar la expresión génica.
- Identificar genes diferencialmente expresados.
- Interpretar resultados mediante análisis funcional. 

## ESTRUCTURA

El proyecto está dividido en varias carpetas.

### Documentos

En esta carpeta se guardarán los archivos complementarios, presentaciones, esquemas, etc; que serán de utilidad para el proyecto.

### Datasets

En esta carpeta se guardarán las bases de datos del proyecto.

### SRC

En esta carpeta se guardarán los archivos con código que usaremos en el proyecto.

## HERRAMIENTAS

- *FastQC*: Calidad de las secuencias.

- *Trimmomatic* o *Cutadapt*: Filtración y recorte.

- *STAR* / *HISAT2*: Alineación del RNA-Seq.

- *FeatureCounts* / *HTSeq-count*: Cuantificación de la expresión génica.

- *DESeq2* / *EdgeR*: Análisis diferencial.

- *ggplot2*, *ComplexHeatmap*: Visualización.

