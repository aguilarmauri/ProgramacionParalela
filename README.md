# Canny
 Parallel Canny's Algorithm

Algoritmo de Canny paralelizado con OpenMP, MPI y CUDA C

## INTRODUCCIÓN
En el área de procesamiento de imágenes, la detección de los bordes de una
imagen es de suma importancia y utilidad, pues facilita muchas tareas, entre ellas, el
reconocimiento de objetos, la segmentación de regiones, entre otras. Se han desarrollado
variedad de algoritmos que ayudan a solucionar este inconveniente.
El algoritmo de Canny es usado para detectar todos los bordes existentes en una
imagen. Este algoritmo está considerado como uno de los mejores métodos de detección
de contornos mediante el empleo de máscaras de convolución y basado en la primera
derivada. Los puntos de contorno son como zonas de píxeles en las que existe un cambio
brusco de nivel de gris. En el tratamiento de imágenes, se trabaja con píxeles, y en un
ambiente discreto, es así que en el algoritmo de Canny se utiliza máscaras, las cuales
representan aproximaciones en diferencias finitas.
En el presente trabajo se realizó la implementación del algoritmo de Canny con
OpenMP, MPI y CUDA, a fin de estudiar en qué medida la programación paralela nos
permite acelerar la ejecución de grandes volúmenes de datos.
