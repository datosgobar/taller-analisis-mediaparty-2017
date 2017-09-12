# Datos: de las fuentes a la exploración analítica

Taller de análisis exploratorio de datos dado en la [MediaParty 2017](http://mediaparty.info/).
Se puede consultar el detalle del taller en la [agenda del evento](http://sched17.mediaparty.info/event/BfsY/datos-de-las-fuentes-a-la-exploracion-analitica).

## Pre-requisitos e instalación del proyecto

Es necesario contar con `python 2.7` o `python 3.x` y tener instaladas las librerias `jupyter`, `pandas` y `matplotlib`. Estas dependencias se encuentran listadas en el archivo `requirements.txt` y pueden ser instaladas mediante el gestor de paquetes `pip` usando el comando

```
pip install -r requirements.txt
```

Una vez instaladas todas las dependencias, ejecutar desde la carpeta raiz del proyecto el comando `jupyter notebook`. Esto levantará un servidor en la maquina local y en el puerto 8888, el cual puede consultarse entrando con un navegador a la dirección [http://localhost:8888](http://localhost:8888).

Es recomendable usar [virtualenv](https://virtualenv.pypa.io/en/stable/) parar evitar conflictos y colisiones en caso de tener instaladas otras versiones de las librerías.

Los ejemplos de análisis de datos de este taller usan el [conjunto de datos de nombres argentinos](http://datos.gob.ar/dataset/nombres-personas-fisicas) registrados entre 1922 y 2015. Descargar el archivo histórico y descomprimirlo en la carpeta raiz del proyecto.

## Librerias y herramientas usadas en el taller

* [`pandas`](http://pandas.pydata.org/): Estructuras y herramientas para análisis de datos en Python.
* [`numpy`](http://www.numpy.org/): Objetos y estructuras para computación científica en Python.
* [`matplotlib`](http://matplotlib.org/): Gráficos en Python.
* [Jupyter](http://jupyter.org/): El notebook para ejecutar código dinámicamente.

## Enlaces de interés

* [Portal de datos de la nación Argentina](http://datos.gob.ar/)
* [Conjunto de datos de nombres registrados en el Registro Nacional de las Personas](http://datos.gob.ar/dataset/nombres-personas-fisicas)
