# Glass Project
## EDA - Data Visualization - Machine Learning

![Jupyter-Notebook](https://jupyter.org/assets/logos/rectanglelogo-greytext-orangebody-greymoons.svg)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

### Problema en cuestión
El estudio de la clasificación de los tipos de vidrio estuvo motivado por la investigación criminológica. En la escena del crimen, el cristal puede usarse como evidencia... ¡si se identifica correctamente!

### Acercamiento a la creación del cristal flotado
El cristal o vidrio flotado consiste en una plancha de vidrio fabricada haciendo flotar el vidrio fundido sobre una capa de estaño también fundido. Este método proporciona al vidrio un grosor uniforme y una superficie muy plana, por lo que es el vidrio más utilizado en la construcción. Se le denomina también vidrio plano, sin embargo no todos los vidrios planos son vidrios fabricados mediante este sistema.

## Features 👀
1. RI: Indice de refracción
3. Na: Sodio (unidad de medida: peso porcentual correspondiente al óxido que contiene)
4. Mg: Magnesio
5. Al: Aluminio
6. Si: Silicio
7. K: Potasio
8. Ca: Calcio
9. Ba: Bario
10. Fe: Hierro
11. Tipo de vidrio o cristal:

<li>1. Ventana construida mediante proceso flotado<br>
<li> 2. Ventana construida mediante proceso no flotado<br>
<li>3. Parabrisas construido mediante proceso flotado<br>
<li>4. Parabrisas construido mediante proceso no flotado (no hay registros en el dataset)<br>
<li>5. Contenedores de cristal<br>
<li>6. Vajilla de cristal<br>
<li>7. Faros de cristal

## Tecnologías 🛡

Este proyecto contiene las siguientes librerias:
- [Pandas](https://pandas.pydata.org/) - Manipulación de datos
- [Numpy](https://numpy.org/) - Manipulación de arrays
- [Matplotlib](https://matplotlib.org/stable/index.html) - Visualización
- [Seaborn](https://seaborn.pydata.org/index.html) - Visualización
- [Sklearn](https://scikit-learn.org/stable/) - Machine Learning (Modelado)
- [Auto-sklearn](https://automl.github.io/auto-sklearn/master/index.html#) - AutoML (Selección del modelo) 

## Instalación 🛠

Este proyecto (si se desea ejecutar en su ordenador de forma local) requiere de un sistema operativo Linux, la extensión de Jupyter en su IDE de preferencia y  [Python3.9](https://www.python.org/) en adelante.

Luego de clonar el repositorio o haberlo descargado, abra la terminal (en la ruta donde se ecuentra el repositorio local) y escriba el siguiente comando:

```
pip install -r packages.txt
```
Con esto se descargarán e instalarán los paquetes necesarios.
Para instalar auto-sklearn se recomienda leer la documentación oficial ya que se necesitan ciertos [requerimientos](https://automl.github.io/auto-sklearn/master/installation.html).


## Autor 🖋
*Franco Nicolás Alarcón*
