# Ejercicio 01 - Mi primera pantalla

## Qué he aprendido
- La estructura básica y componentes primitivos de React Native: `View`, `Text` y `StyleSheet`.
- El funcionamiento de Flexbox en React Native:
  - `flex: 1` para que el contenedor raíz ocupe todo el espacio disponible en pantalla.
  - `justifyContent: 'center'` para alinear los elementos en el eje principal (vertical por defecto).
  - `alignItems: 'center'` para centrar los elementos en el eje transversal (horizontal por defecto).
- La forma de declarar estilos usando `StyleSheet.create()` mediante objetos JavaScript/TypeScript en lugar de hojas de estilo CSS tradicionales.

## Respuesta a la pregunta de comprensión
Explica con tus palabras la diferencia entre el componente `View` y el componente `Text`.

Respuesta:
- **`View`**: Es el componente contenedor fundamental de React Native (equivalente a una etiqueta `<div>` o contenedor en la web). Su propósito principal es estructurar la interfaz, organizar el layout mediante Flexbox, agrupar otros componentes y aplicar propiedades de caja como márgenes, rellenos (`padding`), bordes y colores de fondo. Un `View` **no** puede albergar texto plano directamente sin un componente `Text`.
- **`Text`**: Es el componente encargado exclusivamente de renderizar y dar estilo a cadenas de texto (similar a etiquetas como `<p>`, `<span>` o `<h1>` en la web). En React Native es obligatorio que cualquier texto mostrado en pantalla esté envuelto dentro de un componente `<Text>`, ya que no existe el renderizado de texto directo en contenedores genéricos.

## Qué he modificado
- He añadido el componente `<Text>` correspondiente a `"Curso 2026/27"` para coincidir con la referencia visual del preview propuesto.
- He creado una nueva regla de estilo `course` con `marginTop: 24`, tamaño de fuente `fontSize: 14` y un tono más tenue (`color: '#94a3b8'`).
- He ajustado las proporciones y colores de los estilos `title` y `subtitle` para mejorar la jerarquía visual de la pantalla.

## Resultado
La interfaz muestra una pantalla limpia con fondo claro (`#f1f5f9`), centrada tanto horizontal como verticalmente. En el centro destaca de forma prominente el título principal en negrita ("React Native"), seguido de un subtítulo en gris intermedio ("Mi primera pantalla"), y separado con un margen mayor se muestra la referencia al curso ("Curso 2026/27") en un tamaño y tono más sutil, cumpliendo con la jerarquía visual requerida.
