
# Identificación de células en datos de secuenciación unicelulares utilizando machine learning  

Este repositorio contiene el código y los datos utilizados para el Trabajo de Fin de Grado: “Identificación de células raras en scRNA-seq mediante scNovel”. Se ha realizado dos pipelines diferentes. El primero consiste en la detección de células raras/novedosas en un conjunto de células cerebrales mediante un flujo de trabajo basado en aprendizaje automático supervisado utilizando un conjunto de datos de células cerebrales. La segunda experimentación consiste en detectar grupos/clusters de células con un perfil transcripcional atípico siguiendo un flujo de trabajo de aprendizaje no supervisado (clustering) y utilizando un conjunto de células de sangre periférica para ello.

## Características principales
- Preprocesamiento de datos scRNA-seq
- Clustering no supervisado
- Implementación y evaluación de scNovel
- Cálculo de métricas (AUROC)

## Requisitos
- Python 3.10
- pandas, scanpy, numpy, matplotlib
- scNovel

![image](https://github.com/user-attachments/assets/e40952f8-5aa2-4b2e-a7a3-28f17b239e34)
(Flujo de ejecución de scNovel y su estructura)
