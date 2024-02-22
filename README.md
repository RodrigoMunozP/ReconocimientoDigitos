# Reconocimiento de Dígitos con TensorFlow y MNIST
Este proyecto implementa una red neuronal convolucional (CNN) para el reconocimiento de dígitos escritos a mano, utilizando TensorFlow y el conjunto de datos MNIST. El objetivo es desarrollar un modelo capaz de identificar dígitos del 0 al 9 con alta precisión.

## Características
-Uso de TensorFlow para construir y entrenar el modelo CNN.
-Preprocesamiento de imágenes con ImageDataGenerator para mejorar la generalización.
-Visualización de dígitos y predicciones para evaluación cualitativa.

## Dependencias
-numpy
-tensorflow
-matplotlib

## Conjunto de Datos
El proyecto utiliza el conjunto de datos MNIST, que está disponible directamente a través de TensorFlow. Este conjunto de datos contiene 60,000 imágenes de entrenamiento y 10,000 imágenes de prueba de dígitos escritos a mano, en escala de grises y de tamaño 28x28.

## Modelo
### La CNN implementada incluye las siguientes capas:
-Capas convolucionales para la extracción de características.
-Capas de pooling para reducir la dimensionalidad.
-Capas de dropout para evitar el sobreajuste.
-Una capa flatten para convertir los mapas de características en un vector.
-Capas densas para la clasificación final.

## Entrenamiento
El modelo se entrena con imágenes preprocesadas para incluir rotaciones, desplazamientos y zoom. Esto mejora la capacidad del modelo para reconocer dígitos bajo diversas transformaciones.
