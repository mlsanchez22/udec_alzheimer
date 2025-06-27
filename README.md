# Validación de dianas terapéuticas (T4) en Alzheimer

Análisis de expresión génica (microarrays y scRNA-seq) para validar posibles dianas terapéuticas (T4) en Alzheimer. Proyecto desarrollado durante una estancia en el Departamento de Farmacología de la Universidad de Concepción.

---

## Datos

Los datos crudos originales no se incluyen en este repositorio debido a su tamaño elevado.

### Cómo obtener los datos

Los datasets utilizados están disponibles públicamente en las siguientes fuentes:

- GEO (Gene Expression Omnibus): [Enlace al dataset 1](#)  <!-- reemplaza con el enlace real -->

Se recomienda descargar los datos directamente desde estas plataformas para reproducir los análisis.

---

## Estructura del repositorio

 - `microarray/`: Análisis de microarrays con su propia estructura:
    - `data/`: Datos específicos del análisis de microarrays.  
    - `results/`: Resultados específicos del análisis de microarrays.  
    - `code/`: Scripts y notebooks específicos para microarrays.
  - `sncell/`: Análisis de single-cell RNA-seq con estructura similar:
    - `data/`: Datos específicos del análisis scRNA-seq.  
    - `results/`: Resultados específicos del análisis scRNA-seq.  
    - `code/`: Scripts y notebooks específicos para scRNA-seq.

---

## Entorno de trabajo

Para garantizar la reproducibilidad, se utilizó un entorno virtual gestionado con **conda**.

### Crear el entorno desde el archivo `environment.yml`

Para crear el entorno con las dependencias exactas usadas, ejecuta:

```bash
conda env create -f environment.yml
conda activate r_py_omics_env
