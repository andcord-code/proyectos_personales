# Proyecto Clasificación de Imágenes con CNN en CIFAR-10

Este proyecto tiene como objetivo construir y entrenar una Red Neuronal Convolucional (CNN) para clasificar imágenes del dataset CIFAR-10, que contiene imágenes en color de 10 categorías diferentes.

## Descripción del Dataset

El dataset CIFAR-10 contiene 60,000 imágenes de 32x32 píxeles divididas en 10 clases:

- Avión
- Automóvil
- Pájaro
- Gato
- Ciervo
- Perro
- Rana
- Caballo
- Barco
- Camión

Las imágenes están divididas en un conjunto de entrenamiento de 50,000 imágenes y un conjunto de prueba de 10,000 imágenes.

## Tecnologías utilizadas

- **Python**  
- **TensorFlow y Keras** para construir y entrenar la CNN  
- **NumPy** para manipulación de datos  
- **Matplotlib** para visualización de imágenes y resultados  
- **Jupyter Notebook** para desarrollo interactivo  

## Proceso del proyecto

El proyecto sigue los siguientes pasos:

- Carga y preprocesamiento del dataset CIFAR-10 (normalización y categorización de etiquetas)
- Visualización de muestras del dataset
- Construcción de una arquitectura CNN con varias capas convolucionales, de pooling y capas densas  
- Compilación y entrenamiento del modelo con el optimizador Adam y función de pérdida categórica cruzada  
- Evaluación del desempeño del modelo en el conjunto de prueba  
- Visualización de la curva de aprendizaje (precisión y pérdida en entrenamiento y validación)  
- Pruebas de predicción con imágenes individuales del dataset  

## Resultados

El modelo alcanzó un nivel de precisión adecuado para la clasificación de las 10 categorías del CIFAR-10, demostrando la capacidad de las CNN para resolver problemas de visión por computadora con imágenes pequeñas y en color.

## Archivos

- **CNN_cifar.ipynb**: Notebook con todo el desarrollo, código y análisis.

## Cómo ejecutar el proyecto

1. Clonar o descargar el repositorio.  
2. Instalar las dependencias necesarias:  
   ```bash
   pip install tensorflow numpy matplotlib
   ```
3. Ejecutar el notebook en Jupyter o cualquier entorno compatible.
