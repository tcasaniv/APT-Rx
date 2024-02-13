# Separador de Componentes de Imágenes APT

Este código se encarga de dividir una imagen de transmisión APT (Automatic Picture Transmission) en dos componentes individuales, correspondientes a dos canales de transmisión diferentes. Este proceso es útil cuando se reciben imágenes APT de satélites meteorológicos y se desea separar los datos de cada canal para un análisis más detallado.

## Uso

1. Especifica la ruta de la imagen de transmisión APT que se desea dividir en los componentes individuales en la variable `path_APT_img`.
2. Especifica la ruta donde se guardarán los componentes individuales A y B en las variables `path_APT_img_A` y `path_APT_img_B`.
3. Ejecuta el código.

## Requisitos

- Python 3.x
- Librerías necesarias (instaladas con `pip install pillow`)

## Funcionalidades

- **División de Imágenes**: Divide una imagen de transmisión APT en dos componentes individuales correspondientes a dos canales de transmisión diferentes.

## Notas

- Este script asume que la imagen de transmisión APT tiene una estructura específica con componentes claramente definidos.
- Los nombres de las variables `path_APT_img`, `path_APT_img_A` y `path_APT_img_B` deben ajustarse según la ubicación y el nombre de los archivos de imagen APT.

¡Disfruta separando los componentes de tus imágenes de transmisión APT para un análisis más detallado!