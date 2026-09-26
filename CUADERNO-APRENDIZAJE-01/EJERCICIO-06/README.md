# Ejercicio 06 - Dashboard de métricas

## Qué he aprendido
- A construir diseños en cuadrícula (grid) utilizando la propiedad `flexWrap: 'wrap'` combinada con `flexDirection: 'row'`.
- A distribuir tarjetas en filas con porcentajes de ancho (`width: '48%'`) para que quepan dos elementos por línea.
- A utilizar un componente reutilizable (`Metric`) con paso de parámetros (props) para evitar duplicar código estructurado.

## Respuesta a la pregunta de comprensión
¿Por qué un ancho del 48% puede ser más práctico que 50% cuando además existe separación entre tarjetas?

Respuesta:
Porque si cada tarjeta ocupara exactamente el 50%, sumado al espacio de separación (`gap` o márgenes) entre ellas, se pasaría del 100% del ancho disponible en la fila, haciendo que la segunda tarjeta baje a la línea siguiente de forma descontrolada. Usar un 48% deja un pequeño margen libre que compensa el espacio del `gap`, permitiendo que dos tarjetas encajen perfectamente una al lado de la otra.

## Qué he modificado
- He implementado un componente personalizado de métricas para mostrar cinco tarjetas dinámicas con diferentes valores de ventas, clientes, pedidos, conversión y tickets.
- He adaptado la paleta de colores general al fondo oscuro del cuaderno y añadido un verde llamativo para los indicadores de crecimiento positivo.

## Resultado
La interfaz muestra un panel de control (dashboard) organizado con un título principal y una cuadrícula limpia de tarjetas blancas de métricas distribuidas en parejas de dos por fila.