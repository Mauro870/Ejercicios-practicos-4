# Ejercicios-practicos-4

E1.Implemente la convolución unidimensional entre los siguientes polinomios:

P(x) = 2x^3+3x^2+6x+7 y h(x) = x+2

Tips:
• Para desplazar el polinomio h sobre el polinomio P puede usar la función shift de la librería scipy.ndimage.interpolation
• Para reflejar el polinomio h puede utilizar la función flip

E2. Haga un sencillo filtrado (detección de bordes) a la imagen lenna.png utilizando el kernel Sobel y la convolución en dos dimensiones. Kernel Sobel horizontal: sobel_h = [[-1,-2,-1],[0,0,0],[1,2,1]] Kernel Sobel vertical: sobel_v = [[-1,0,1],[-2,0,2],[-1,0,1]] • Para poder trabajar con la imagen debe bajarla a escala de grises eliminando la última componente de la matriz de la imagen. • Para cargar la imagen puede utilizar la función pylab.imread('lenna.png’) • Para mostrar una imagen puede utilizar la función pylab.imshow(arreglo_imagen, cmap=pyl.cm.gray)

E3.En el siguiente enlace: https://nptel.ac.in/courses/111107062/module3/lecture1/lecture1.pdf se describe un algoritmo que sirve para calcular el valor propio (eigenvalue) dominante de una matriz cuadrada de dimensión 3, utilice la librería numpy para implementar ese algoritmo en Python. Utilizando su función encuentre el valor propio de la matriz:
