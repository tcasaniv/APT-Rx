# APT-Rx
Este programa decodifica un archivo de audio en formato APT (Automatic Picture Transmission) en formato WAV para obtener una imagen en escala de grises y en falso color.

## Recepcionar audio APT con RTL-SDR

Puedes recepcionar un audio APT en WAV con un RTL-SDR v3/v4 con el siguiente comando:
```bash
rtl_fm -s 115000 -f 137500000 "./Files_Rx/audio_FM_Rx.wav"
```
El comando recepciona y demodula FM con una frecuencia de muestreo (samplerate) de 115kHz a una frecuencia central de 137.5 MHz y lo guarda en la ruta `./Files_Rx/audio_FM_Rx.wav`.


## APT Decoder

Este programa decodifica archivos de audio en formato APT (Automatic Picture Transmission) en archivos de imagen en escala de grises. La transmisión APT es comúnmente utilizada en satélites meteorológicos y de inteligencia para transmitir imágenes.

### Características Principales

- Decodificación de archivos de audio en formato WAV en imágenes en escala de grises.
- Permite ajustar los parámetros para definir los límites de rango dinámico de la imagen.
- Filtrado de ruido para mejorar la calidad de la imagen.
- Guardado de la imagen decodificada y los componentes individuales de la imagen.

### Uso

1. Especifica la ruta del archivo de audio APT en formato WAV que se va a decodificar.
2. Ajusta los parámetros opcionales según sea necesario.
3. Ejecuta el código.

## APT Falso Color Básico

Este programa aplica un efecto de falso color a una imagen en escala de grises, utilizando diferentes mapas de colores predefinidos. El falso color es una técnica de visualización que asigna colores a valores específicos en una imagen para resaltar detalles o características.

### Funcionalidades

- **Aplicación de Falso Color**: Utiliza el mapa de colores seleccionado para aplicar el efecto de falso color a la imagen en escala de grises.
- **Guardado de Imagen**: Guarda la imagen con falso color en la ruta especificada.

### Uso

1. Especifica la ruta de la imagen en escala de grises que se desea convertir en falso color en la variable `path_raw_img`.
2. Especifica la ruta de salida para guardar la imagen con falso color en la variable `out_path`.
3. Selecciona el mapa de colores para el falso color utilizando la lista desplegable de `colormap_overlay`.
4. Ejecuta el código.

## APT Falso Color Avanzado

Este programa aplica un efecto de falso color avanzado a dos imágenes en escala de grises, combinando las características de ambas imágenes para resaltar detalles y mejorar la interpretación visual.

### Funcionalidades

- **Combinación de Imágenes**: Utiliza las características de dos imágenes en escala de grises para aplicar un efecto de falso color avanzado.
- **Personalización Avanzada**: Permite ajustar la mezcla de infrarrojos y el realce de color de la tierra para obtener resultados deseados.
- **Guardado de Imagen**: Guarda la imagen resultante con falso color en la ruta especificada.

### Uso

1. Especifica las rutas de las imágenes A y B en escala de grises que se desean combinar para aplicar el falso color.
2. Especifica la ruta de salida para guardar la imagen con falso color.
3. Configura las variables para personalizar el efecto de falso color avanzado, como la mezcla de infrarrojos y el realce de color de la tierra.
4. Ejecuta el código.

## Separador de Componentes de Imágenes APT

Este código se encarga de dividir una imagen de transmisión APT (Automatic Picture Transmission) en dos componentes individuales, correspondientes a dos canales de transmisión diferentes. Este proceso es útil cuando se reciben imágenes APT de satélites meteorológicos y se desea separar los datos de cada canal para un análisis más detallado.

### Uso

1. Especifica la ruta de la imagen de transmisión APT que se desea dividir en los componentes individuales en la variable `path_APT_img`.
2. Especifica la ruta donde se guardarán los componentes individuales A y B en las variables `path_APT_img_A` y `path_APT_img_B`.
3. Ejecuta el código.

### Funcionalidades

- **División de Imágenes**: Divide una imagen de transmisión APT en dos componentes individuales correspondientes a dos canales de transmisión diferentes.
