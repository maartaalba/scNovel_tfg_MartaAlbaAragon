
# Identificación de células en datos de secuenciación unicelulares utilizando machine learning  

Este repositorio contiene el código y los datos utilizados para el Trabajo de Fin de Grado: “Identificación de células raras en scRNA-seq mediante scNovel”. Se ha realizado dos pipelines diferentes. 

El primero consiste en la detección de células raras/novedosas en un conjunto de células cerebrales mediante un flujo de trabajo basado en aprendizaje automático supervisado utilizando un conjunto de datos de células cerebrales. 

La segunda experimentación consiste en detectar grupos/clusters de células con un perfil transcripcional atípico siguiendo un flujo de trabajo de aprendizaje no supervisado (clustering) y utilizando un conjunto de células de sangre periférica para ello.

El algoritmo scNovel está diseñado específicamente para la detección automática de tipos celulares raros y novedosos. Su principal objetivo es identificar poblaciones celulares previamente no caracterizadas o extremadamente poco representadas dentro de conjuntos de datos con gran dimensión, superando las limitaciones de los métodos tradicionales que dependen de referencias conocidas o de la presencia de genes marcadores bien definidos. 

## Características principales
- Preprocesamiento de datos scRNA-seq
- Clustering no supervisado
- Implementación y evaluación de scNovel
- Cálculo de métricas (AUROC)

## Requisitos
- Python 3.10
- pandas, scanpy, numpy, matplotlib
- scNovel

## Material proporcionado
- Jupyter Notebook de la experimentación con el conjunto de datos de células cerebrales (Darmanis) en formato .ipynb y HTML
- Jupyter Notebook de la experimentación con el conjunto de datos de células de sangre periférica (PBMC3k) en formato .ipynb y HTML
- Archivos CSV con la información de las etiquetas y conteo de la expresión génica del conjunto de datos Darmanis.

El conjunto de datos PBMC3k ha sido implementado usando una función de Scanpy (sc.datasets.pbmc3k()) 
  

![image](https://github.com/user-attachments/assets/e40952f8-5aa2-4b2e-a7a3-28f17b239e34)
(Flujo de ejecución de scNovel y su estructura)
