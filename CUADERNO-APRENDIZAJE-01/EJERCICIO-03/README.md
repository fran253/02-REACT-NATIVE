# Ejercicio 03 - Ficha de perfil

## Qué he aprendido
- A integrar imágenes remotas utilizando el componente `Image` de React Native mediante URLs.
- A redondear imágenes cuadradas para convertirlas en círculos exactos aplicando un `borderRadius` igual a la mitad de su tamaño.
- A distribuir elementos en horizontal utilizando `flexDirection: 'row'` y a separarlos con la propiedad `gap`.

## Respuesta a la pregunta de comprensión
Si quieres que dos estadísticas aparezcan una al lado de otra, ¿en qué View aplicarías `flexDirection: 'row'` y por qué?

Respuesta:
Se aplica en el `View` contenedor que agrupa a los bloques de las estadísticas (en este caso, el contenedor con estilo `stats`), porque por defecto React Native organiza los elementos en columna (`column`). Al cambiarlo a `row`, haces que todos sus hijos directos se coloquen en fila horizontalmente.

## Qué he modificado
- He ampliado el ejemplo base añadiendo un tercer bloque de estadística ("Contactos") junto a proyectos y seguidores.
- He adaptado la paleta de colores para mantener la consistencia con los ejercicios anteriores, utilizando un fondo general oscuro (`#1e293b`).

## Resultado
La interfaz muestra una tarjeta de perfil centrada con una foto de avatar redonda, el nombre y la profesión, seguida de una fila horizontal que agrupa limpiamente las tres estadísticas (proyectos, seguidores y contactos).