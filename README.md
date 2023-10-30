# Proyecto - 1: Tuning-hyperparameters

## data
Contiene archivos de interes
* fire_images.jsonl - usado para generar el train_annotations.jsonl y el validation_annotations.jsonl
* python_model.pkl - mejor modelo entrenado almacenado en un archivo binario.
* test-images - imagenes de prueba utilizadas para hacer las inferencias en el modelo deployado.
* training-mltable-folder - contiene un MLTable y el archivo jsonl para entrenamiento.
* validation-mltable-folder - contiene un MLTable y el archivo jsonl para validación.

### data-preprocessing.ipynb
Notebook con la implementación necesaria para cargar el dataset en el blob storage y crear el archivos jsonl

### orchestrator_cluster.ipynb
Notebook con la implementación necesaria para crear un cluster, job, entrenar los modelos, desplegar el modelo con mejores metricas y deslegarlo para realizar inferencias con las imagenes de prueba.

### orchestrator-hp.ipynb
Notebook con la implementación necesaria para el tuneo de hiperparametros

## dataset
Link del dataset utilizado en el proyecto:  

[https://www.kaggle.com/datasets/phylake1337/fire-dataset/]