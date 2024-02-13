# Falso Color Básico

Este programa aplica un efecto de falso color a una imagen en escala de grises, utilizando diferentes mapas de colores predefinidos. El falso color es una técnica de visualización que asigna colores a valores específicos en una imagen para resaltar detalles o características.

## Uso

1. Especifica la ruta de la imagen en escala de grises que se desea convertir en falso color en la variable `path_raw_img`.
2. Especifica la ruta de salida para guardar la imagen con falso color en la variable `out_path`.
3. Selecciona el mapa de colores para el falso color utilizando la lista desplegable de `colormap_overlay`.
4. Ejecuta el código.

## Requisitos

- Python 3.x
- Librerías necesarias (instaladas con `pip install numpy matplotlib pillow`)

## Funcionalidades

- **Aplicación de Falso Color**: Utiliza el mapa de colores seleccionado para aplicar el efecto de falso color a la imagen en escala de grises.
- **Guardado de Imagen**: Guarda la imagen con falso color en la ruta especificada.

## Mapas de Colores Disponibles

- `'flag'`
- `'prism'`
- `'ocean'`
- `'gist_earth'`
- `'terrain'`
- `'gist_stern'`
- `'gnuplot'`
- `'gnuplot2'`
- `'CMRmap'`
- `'cubehelix'`
- `'brg'`
- `'gist_rainbow'`
- `'rainbow'`
- `'jet'`
- `'turbo'`
- `'nipy_spectral'`
- `'gist_ncar'`

## Notas

- El falso color es útil para resaltar características específicas en una imagen y mejorar su interpretación visual.
- La elección del mapa de colores puede afectar significativamente la apariencia de la imagen con falso color.
- `'gist_earth'` es el ideal para mapas geográficos, pero `'cubehelix'` es una buena opción para otro tipo de imágenes.

¡Experimenta con diferentes mapas de colores para obtener resultados interesantes!