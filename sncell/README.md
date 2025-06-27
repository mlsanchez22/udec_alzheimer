# Análisis de Single-cell RNA-seq (scRNA-seq)

Este directorio contiene los scripts y resultados del análisis de transcriptómica de célula única (scRNA-seq) orientado a la validación de posibles dianas terapéuticas (T4) relacionadas con la enfermedad de Alzheimer.

## Datos fuente y grupos de pacientes

Los datos analizados provienen del siguiente estudio:

- **Serrano-Pozo A** *et al.* (2024). *Astrocyte transcriptomic changes along the spatiotemporal progression of Alzheimer's disease.* Nat Neurosci. 27(12):2384-2400.  
  [PMID: 39528672](https://pubmed.ncbi.nlm.nih.gov/39528672)  
  [PMCID: PMC11614739](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11614739)  
  [DOI: 10.1038/s41593-024-01791-4](https://doi.org/10.1038/s41593-024-01791-4)

El estudio incluyó tres grupos principales de pacientes con diferentes estadios de Alzheimer:

- **B1:** Controles o Alzheimer preclínico.  
- **B2:** Alzheimer temprano a moderado.  
- **B3:** Alzheimer avanzado.

Debido a la elevada capacidad computacional requerida para el análisis, se seleccionaron exclusivamente los grupos B1 y B2, descartando B3, dado que en el Alzheimer avanzado el tratamiento sería menos efectivo.

## Estructura del análisis

El análisis se divide en dos scripts/notebooks principales:

- **`01_parser_metadatos.ipynb`**  
  Script en Python encargado de procesar y organizar los metadatos clínicos y experimentales.

- **`02_expresion_diferencial_celulas.ipynb`**  
  Script en R que realiza el análisis de expresión diferencial a nivel celular usando los datos procesados.

