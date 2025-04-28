# Actividad-2.2.-Redes-Neuronales-Reconocimiento-de-Rostros

Este proyecto permite tomar una foto con la cámara web en Google Colab, detectar rostros en la imagen utilizando un modelo de Deep Learning basado en OpenCV, y mostrar la imagen con las caras detectadas.

## El flujo general del programa

1.- Se activa la cámara web desde el navegador usando JavaScript.

2.- El usuario captura una foto, que se guarda localmente.

3.- La imagen se redimensiona para facilitar el procesamiento.

4.- Se descargan los archivos necesarios de un modelo preentrenado de detección de rostros (basado en redes neuronales convolucionales).

5.- Se carga la imagen en el modelo, que detecta posibles rostros.

6.- Se dibujan rectángulos rojos alrededor de los rostros detectados junto con el porcentaje de certeza de cada predicción.

7.- Finalmente, se muestra la imagen procesada.

Este proyecto es una demostración sencilla de cómo combinar OpenCV, modelos preentrenados y funciones interactivas en Colab para trabajar con imágenes en tiempo real.
