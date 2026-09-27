# Ejercicio 08 - Catálogo con FlatList

## Qué he aprendido
- A utilizar el componente `FlatList` para renderizar listas eficientes a partir de un array de datos en lugar de repetir código estático.
- A configurar propiedades clave como `data`, `keyExtractor` para identificar cada elemento de forma única, y `renderItem` para definir la estructura visual de las tarjetas.
- A organizar el catálogo en una cuadrícula utilizando `numColumns` y `columnWrapperStyle` para gestionar el espaciado entre filas.

## Respuesta a la pregunta de comprensión
¿Qué ventaja tiene cambiar un producto en el array en lugar de buscar su tarjeta manualmente dentro del JSX?

Respuesta:
La principal ventaja es que al centralizar los datos en el array, cualquier modificación, adición o eliminación se actualiza de forma automática y dinámica en la interfaz gracias al `FlatList`. Si estuviera escrito en JSX estático, tendrías que buscar y modificar manualmente el código de cada tarjeta en la pantalla, lo que hace que el mantenimiento sea mucho más lento y propenso a errores.

## Qué he modificado
- He ampliado el catálogo base añadiendo dos productos adicionales al array (portátil y móvil) junto con sus respectivos iconos y precios.
- He adaptado la paleta de colores general al fondo oscuro del cuaderno y configurado la cuadrícula para mostrar los elementos en parejas organizadas.

## Resultado
La interfaz muestra un catálogo de productos desplazable y estructurado en una cuadrícula limpia de dos columnas, renderizado de manera automática a partir de los datos definidos en el array.