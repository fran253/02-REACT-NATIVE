# Ejercicio 09 - Interfaz bancaria

## Qué he aprendido
- A estructurar pantallas complejas combinando componentes de desplazamiento vertical (`ScrollView`) con tarjetas de contenido destacado.
- A encapsular elementos repetitivos en un componente reutilizable (`Movement`) tipificado con TypeScript mediante `MovementProps`.
- A organizar la jerarquía visual de una aplicación financiera aplicando contrastes de color, tamaños y distribuciones en fila con Flexbox.

## Respuesta a la pregunta de comprensión
¿Qué partes de esta pantalla convertirías en componentes y cuáles dejarías directamente en App? Justifica.

Respuesta:
Convertiría en componentes independientes los elementos repetitivos o complejos que pueden reutilizarse, como las tarjetas de movimientos (`Movement`), ya que comparten estructura y solo cambian sus datos. En cambio, dejaría directamente en el `App` principal las secciones únicas de la pantalla o la estructura general del layout (como el saludo de bienvenida o la tarjeta principal de saldo), puesto que solo aparecen una vez y no justifican la creación de un componente exclusivo.

## Qué he modificado
- He adaptado la interfaz completa al fondo oscuro característico del cuaderno de prácticas (`#1e293b`), ajustando los colores del texto, la tarjeta de saldo en un tono oscuro elegante y las filas de movimientos en tarjetas blancas.
- He estructurado un listado de transacciones financieras con cuatro movimientos detallados (supermercado, cafetería, nómina y electricidad).

## Resultado
La interfaz muestra el panel de una aplicación bancaria moderna con un saludo personalizado, una tarjeta prominente con el saldo disponible y un listado limpio de los últimos movimientos ordenados verticalmente.