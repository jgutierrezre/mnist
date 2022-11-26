Detección de digitos e interpretación de digitos | Análisis de Bases de Datos | 2022-II
=======================================================================================
> Juan Pablo Gutiérrez Restrepo

### Instalación

Descargar `emnist-digits-test.csv` y `emnist-digits-train.csv` del [siguiente](https://www.kaggle.com/datasets/crawford/emnist) enlace.

Descomprimir los archivos de `emnist-digits-test.csv.zip` y `emnist-digits-train.csv.zip` en la carpeta `data`.

Cargar imagenes de digitos en `input`. Deben ser sobre fondo blanco para funcionar.

El directorio debe quedar asi:

    .
    ├── data                        # Dataset files
    |   |
    │   ├── .placeholder
    │   ├── emnist-digits-train.csv
    │   └── emnist-digits-test.csv
    |
    ├── input                       # Image files
    |   |
    │   ├── *.*                     # Any supported format (.jpg, .png, etc...)
    │   └── ...
    |
    ├── mnist.ipynb                 # Main Notebook
    |
    └── ...

Correr `mnist.ipynb` y seguir las instrucciones.