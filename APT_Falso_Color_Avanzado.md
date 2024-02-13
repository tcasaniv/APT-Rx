# Falso Color Avanzado

Este programa aplica un efecto de falso color avanzado a dos imágenes en escala de grises, combinando las características de ambas imágenes para resaltar detalles y mejorar la interpretación visual.

## Uso

1. Especifica las rutas de las imágenes en escala de grises que se desean combinar para aplicar el falso color.
2. Especifica la ruta de salida para guardar la imagen con falso color.
3. Configura las variables para personalizar el efecto de falso color avanzado, como la mezcla de infrarrojos y el realce de color de la tierra.
4. Ejecuta el código.

## Requisitos

- Python 3.x
- Librerías necesarias (instaladas con `pip install numpy matplotlib pillow`)

## Funcionalidades

- **Combinación de Imágenes**: Utiliza las características de dos imágenes en escala de grises para aplicar un efecto de falso color avanzado.
- **Personalización Avanzada**: Permite ajustar la mezcla de infrarrojos y el realce de color de la tierra para obtener resultados deseados.
- **Guardado de Imagen**: Guarda la imagen resultante con falso color en la ruta especificada.

## Configuración para el Falso Color Avanzado

- `ir_blend`: Selecciona el tipo de mezcla de infrarrojos para el falso color avanzado. Opciones disponibles:
  - `-noir`: No realizar mezcla de infrarrojos.
  - `-ir`: Realizar mezcla de infrarrojos.
  - `-ir_night`: Mezcla de infrarrojos para imágenes nocturnas.
  - `-sunset`: Mezcla de infrarrojos para imágenes diurnas.
- `enable_boost`: Activa o desactiva el realce de color de la tierra en imágenes muy azules.

## Notas

- El falso color avanzado combina las características de dos imágenes en escala de grises para resaltar detalles específicos y mejorar la interpretación visual.
- La configuración de las variables `ir_blend` y `enable_boost` puede afectar significativamente la apariencia de la imagen con falso color.

¡Experimenta con diferentes configuraciones para obtener resultados interesantes y únicos en tus imágenes!