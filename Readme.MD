# Procesamiento de Datos Públicos Colombianos con Databricks 

Este proyecto tiene como objetivo descargar, limpiar, transformar y cargar dos conjuntos de datos públicos provenientes del portal de Datos Abiertos de Colombia. El procesamiento se realiza en Databricks, aprovechando su entorno escalable para análisis de datos.

## 📂 Datasets Utilizados

1. *Contratos del Estado (SECOP):*  
   [Descargar CSV](https://www.datos.gov.co/resource/rpmr-utcd.csv)  
   Contiene información sobre contratos estatales registrados en Colombia.

2. *Instituciones Educativas (MEN):*  
   [Descargar CSV](https://www.datos.gov.co/resource/nudc-7mev.csv)  
   Proporciona datos relacionados con las instituciones educativas en el país.

## ⚙️ Procesamiento

Las principales etapas del flujo de trabajo son:

- Carga de datos desde URLs usando SODAPI.
- Inspección y limpieza inicial (valores nulos, formatos inconsistentes, etc.).
- Transformaciones específicas por dataset (filtrado, renombrado de columnas, tipificación de datos).
- Almacenamiento en Databricks como tablas estructuradas para análisis posterior.

## 📊 Objetivos

- Unificar y estandarizar la información para facilitar su análisis.
- Explorar posibles relaciones entre contratos estatales e instituciones educativas.
- Preparar los datos para visualización y explotación con herramientas como Power BI o Notebooks en Databricks. 

## 🚀 Herramientas Utilizadas

- *Python 3.11+* para el procesamiento de datos.
- *Pandas* para manipulación de estructuras tabulares.
- *Databricks* como plataforma de ejecución y almacenamiento.
- *Spark* para operaciones distribuidas (cuando sea necesario).

## 📝 Notas Adicionales

Este repositorio está diseñado para facilitar el acceso a datos limpios y bien estructurados, promoviendo la transparencia, el análisis reproducible y el uso responsable de la información pública.

---