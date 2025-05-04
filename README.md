# Inteligencia Artificial I, Actividad 1: Redes Neuronales
## Consigna
La consigna de esta actividad era de seleccionar uno de los ejemplos presentes en el documento presentado en clase sobre Redes Neuronales y explicar que hace, también se permitía buscar por cuenta propia una Red Neuronal.

Para esta actividad decidí buscar una Red Neuronal por mi cuenta ya que busqué algo lo suficientemente simple para poder correr en mi computadora. La red neuronal que elegí fue una red neuronal convolucional para reconocimiento de imágenes, para ello seguí el siguiente tutorial del canal **Neuralnine**:
https://www.youtube.com/watch?v=CtzfbUwrYGI

La Red Neuronal implementada permite el reconocimiento de imágenes, está diseñada para reconocer:
- aviones
- autos
- pájaros
- ciervos
- gatos
- perro
- ranas
- barcos
- caballos
- camiones

Siguiendo el tutorial probé entrenar la red neuronal con 30 ciclos completos de entrenamiento (epochs), lo que resultó en una precisión de la red neuronal de alrededor del 69%. La red neuronal pudo reconocer la imagen de un perro que descargué de internet, pero no de un avión y de mi perro a quien curiosamente lo clasificó como un barco...
Así que probé aumentando los epochs a 64, lo interesante de esto es que redujo la precisión a un 65.72% pero esta vez sí pudo reconocer a mi perro Kimi como a un perro.

[Link al Jupyter Notebook](https://github.com/fedemaximovicz/tarea_redes_neuronales/blob/master/Main.ipynb)
