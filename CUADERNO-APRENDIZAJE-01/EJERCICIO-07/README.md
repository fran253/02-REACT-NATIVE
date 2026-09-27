# Ejercicio 07 - Feed de noticias

## Qué he aprendido
- A utilizar el componente `ScrollView` para permitir que el contenido de la pantalla se pueda desplazar verticalmente cuando supera la altura del dispositivo.
- A crear componentes reutilizables (`NewsCard`) que reciben datos dinámicos mediante props para evitar repetir código estructural.
- A estructurar listas de tarjetas con márgenes inferiores y espaciados consistentes.

## Respuesta a la pregunta de comprensión
¿Qué parte debe cambiar entre una noticia y otra y qué parte debería permanecer igual?

Respuesta:
Lo que debe cambiar (los datos dinámicos) es el contenido específico de cada noticia, como la categoría y el título. Lo que debe permanecer igual (la estructura y los estilos) es el diseño visual de la tarjeta (`NewsCard`), asegurando que todas compartan la misma forma, colores, bordes y tipografía.

## Qué he modificado
- He adaptado la paleta de colores para mantener la coherencia con los ejercicios anteriores, utilizando un fondo general oscuro (`#1e293b`) y texto en blanco para la cabecera.
- He añadido una nueva tarjeta temática sobre diseño ("Interfaces accesibles") al feed de noticias y he ajustado los tamaños y grosores de fuente en las categorías.

## Resultado
La interfaz muestra un listado de noticias desplazable con un título de cabecera claro y tarjetas blancas individuales que muestran de forma organizada la categoría y el titular de cada artículo.