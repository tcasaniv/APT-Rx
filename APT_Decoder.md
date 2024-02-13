# APT Decoder

Este programa decodifica archivos de audio en formato APT (Automatic Picture Transmission) en archivos de imagen en escala de grises. La transmisión APT es comúnmente utilizada en satélites meteorológicos y de inteligencia para transmitir imágenes.

## Características Principales

- Decodificación de archivos de audio en formato WAV en imágenes en escala de grises.
- Permite ajustar los parámetros para definir los límites de rango dinámico de la imagen.
- Filtrado de ruido para mejorar la calidad de la imagen.
- Guardado de la imagen decodificada y los componentes individuales de la imagen.

## Funcionalidades

- **Decodificación de Imágenes APT**: Transforma archivos de audio WAV en imágenes en escala de grises transmitidas por satélites meteorológicos.
- **Remuestreo de Audio**: Ajusta la velocidad de remuestreo del audio para una decodificación precisa.
- **Transformada de Hilbert**: Obtén información de amplitud (AM) utilizando la transformada de Hilbert.
- **Submuestreo de Señales**: Reduce el tamaño de la señal transformada para obtener las imágenes deseadas.
- **Cuantización de Señales**: Digitaliza la señal para prepararla para la reconstrucción de la imagen.
- **Reconstrucción de Imágenes**: Convierte la información decodificada en imágenes 2D.
- **Filtrado de Ruido**: Elimina filas con alto ruido para mejorar la calidad de la imagen.
- **Guardado de Imágenes**: Permite exportar las imágenes decodificadas para su análisis.

## Uso

1. Especifica la ruta del archivo de audio APT en formato WAV que se va a decodificar.
2. Ajusta los parámetros opcionales según sea necesario.
3. Ejecuta el código.

## Requisitos

- Python 3.x
- Librerías necesarias (instaladas con `pip install numpy scipy matplotlib pillow`)

## Componentes de la Imagen

- **Sync A/B**: Sincronización de la imagen.
- **Space A/B**: Espacio entre los componentes de la imagen.
- **Image A/B**: La imagen capturada.
- **Telemetry A/B**: Telemetría de la imagen.

## Notas

- Este código asume que la señal de audio de entrada contiene una transmisión APT válida.
- Los componentes de la imagen pueden variar dependiendo del formato y la configuración específica de la transmisión APT.
- Es posible que se requieran ajustes adicionales según las características específicas del archivo de audio de entrada.

¡Disfruta decodificando imágenes de transmisiones APT!