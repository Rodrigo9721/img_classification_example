# Ejemplo básico de un modelo de clasificación de imágenes utilizando un modelo preentrenado VGG16 con la base CIFAR-10
 - La base contiene imágenes 32x32 clasificadas en 10 clases
 - Para el fine tuning del modelo, se utiliza un ImageDataGenerator junto con un conjunto de capas propias para trabajar adecuadamente con la base CIFAR-10
 - Al final, se presenta cómo sería el código para el entrenamiento de un modelo similar con una base de datos propia, se mantiene el uso de VGG16