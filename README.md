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

El proyecto está dividido en varias carpetas:

-**Documentos**: En esta carpeta se guardarán los archivos complementarios, presentaciones, esquemas, etc; que serán de utilidad para el proyecto.
-**Datasets**: En esta carpeta se guardarán las bases de datos del proyecto.
-**SRC**: En esta carpeta se guardarán los archivos con el código fuente que usaremos en el proyecto.

## HERRAMIENTAS UTILIZADAS

- *FastQC*: Control de calidad de las secuencias.

- *Trimmomatic* o *Cutadapt*: Filtración y recorte se secuencias.

- *STAR* / *HISAT2*: Alineación del RNA-Seq al genoma de referencia.

- *FeatureCounts* / *HTSeq-count*: Cuantificación de la expresión génica.

- *DESeq2* / *EdgeR*: Análisis de expresión diferencial.

- *R* con los paquetes *ggplot2*, *ComplexHeatmap*: Visualización de datos.

## INSTRUCCIONES DE USO
1. Abrir terminal, clonar el repositorio y ejecutar:
   ```bash
   git clone https://github.com/jetxano/Expresion-genes-project.git
   cd Expresion-genes-project 

2. Instalar las herramientas mencionadas en la sección anterior.
3. Copiar los archivos de secuenciación RNA-Seq dentro de la carpeta Datasets/.
4. Ejecutar los scripts ubicados en SRC/.

## ENLACE AL REPOSITORIO
[Acceder al repositorio](https://github.com/jetxano/Expresion-genes-project)

## LICENCIA
Este proyecto se encuentra bajo la licencia de **[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)**.  
Para más detalles, consulta: [`LICENSE`](LICENSE)

## AUTORES
- [@Marianjucar](https://github.com/Marianjucar)
- [@jetxano](https://github.com/jetxano)
- [@Lumari14](https://github.com/Lumari14)
- [@LydiaSegxvia](https://github.com/LydiaSegxvia)



