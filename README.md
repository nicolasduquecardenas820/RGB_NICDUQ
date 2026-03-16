Análisis de Píxeles y Construcción de una Matriz RGB a partir de una Imagen
Introducción

Las imágenes digitales que vemos diariamente en pantallas están formadas por miles de pequeños puntos llamados píxeles. Cada píxel contiene información numérica que define su color. Comprender esta estructura permite entender cómo las computadoras almacenan y procesan imágenes.

En este proyecto se analiza una imagen del personaje Hulk, utilizando Python en Google Colab para extraer la información de color de cada píxel. A partir de estos datos se construye una matriz RGB, la cual permite observar cómo una imagen puede representarse completamente mediante números.

Además, los datos obtenidos se exportan a archivos de Excel, donde es posible visualizar tanto los valores numéricos de los píxeles como una reconstrucción de la imagen utilizando celdas coloreadas.

Propósito del proyecto

El propósito de este ejercicio es explorar la relación entre imágenes digitales y estructuras de datos, mostrando cómo un archivo gráfico puede transformarse en información organizada que puede ser analizada y manipulada.

Objetivos
Objetivo principal

Analizar la composición de una imagen digital mediante la extracción de sus valores de color y la construcción de una matriz RGB utilizando Python.

Objetivos específicos

Utilizar Python para procesar una imagen digital.

Identificar los valores de color de cada píxel.

Organizar la información de los píxeles en una matriz de datos.

Exportar los resultados a archivos de Excel.

Visualizar cómo una imagen puede representarse mediante datos numéricos.

Imagen utilizada

Para el desarrollo del ejercicio se seleccionó una imagen del personaje Hulk, debido a la variedad de tonos verdes y colores presentes en la ilustración.

Las imágenes digitales utilizan el modelo de color RGB, el cual combina tres canales de color:

Rojo (Red)

Verde (Green)

Azul (Blue)

Cada canal puede tomar valores entre 0 y 255, lo que permite representar una gran cantidad de colores diferentes.

Procedimiento

El desarrollo del proyecto se llevó a cabo mediante los siguientes pasos:

Carga de la imagen
Se importó la imagen en el entorno de programación utilizando librerías especializadas.

Procesamiento de los píxeles
Se recorrió cada píxel de la imagen para obtener sus componentes de color RGB.

Construcción de la matriz de datos
Los valores extraídos se organizaron en una matriz que representa la distribución de colores de la imagen.

Exportación a Excel
Los datos generados se guardaron en archivos de Excel para facilitar su visualización y análisis.

Reconstrucción visual de la imagen
Utilizando los valores de color, se generó un archivo de Excel que recrea la imagen mediante celdas coloreadas.

Resultados

Como resultado del procesamiento de la imagen se generaron dos archivos principales:

Hulk_RGB_Matrix.xlsx
Contiene la matriz con los valores RGB de cada píxel de la imagen.

Hulk_Pixel_Image.xlsx
Presenta una representación visual de la imagen utilizando celdas coloreadas en Excel, simulando los píxeles originales.

Tecnologías utilizadas

Para el desarrollo del proyecto se utilizaron las siguientes herramientas:

Python

Google Colab

Pandas

PIL (Python Imaging Library)

OpenPyXL

Microsoft Excel

Conclusiones

Este ejercicio demuestra cómo una imagen digital puede interpretarse como un conjunto de datos estructurados. Al analizar los valores RGB de cada píxel es posible entender cómo se construyen los colores y cómo las imágenes pueden manipularse mediante programación.

Este tipo de análisis es la base de muchas aplicaciones en áreas como visión por computadora, procesamiento de imágenes y análisis de datos visuales.
