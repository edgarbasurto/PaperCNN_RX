# Análisis de Imágenes Rayos X Cerebrales Usando Redes Neuronales Convolucionales VGGNet

Este proyecto aborda el desarrollo y entrenamiento de un modelo de detección de tumores cerebrales utilizando redes neuronales convolucionales (CNN) basadas en la arquitectura VGGNet16. El objetivo principal es aplicar inteligencia artificial para la interpretación de imágenes médicas de radiografías cerebrales, facilitando la detección temprana de patologías.

## Descripción del Proyecto
- **Recopilación de datos:** Se utiliza un conjunto de imágenes de radiografías cerebrales, clasificadas en dos categorías: "Tumor" y "Healthy".
- **Preprocesamiento:** Se aplican técnicas para normalizar y preparar las imágenes antes del entrenamiento.
- **Modelo:** Se emplea la arquitectura VGGNet16, adaptando la capa de salida para clasificación binaria.
- **Entrenamiento:** Se implementan estrategias como Learning Rate Schedule y EarlyStopping para evitar el sobreaprendizaje. El modelo alcanza una pérdida del 3.92% y una exactitud del 98.68%.

## Conclusiones
La combinación de VGGNet16, técnicas de preprocesamiento y ajustes cuidadosos de hiperparámetros permite obtener un modelo CNN altamente efectivo para la detección de tumores cerebrales en radiografías. Sin embargo, es importante considerar limitaciones como el tamaño del conjunto de datos, la variabilidad de las imágenes y la necesidad de validación clínica antes de su uso en entornos médicos reales.
