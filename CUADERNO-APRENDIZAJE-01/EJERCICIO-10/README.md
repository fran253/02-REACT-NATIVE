# Ejercicio 10 - Proyecto final: Fitness

## Qué he aprendido
- A integrar múltiples conceptos avanzados de diseño en una única pantalla completa utilizando contenedores desplazables (`ScrollView`).
- A componer estructuras visuales complejas combinando barras de progreso personalizadas, cuadrículas en dos columnas con porcentajes de ancho (`width: '48%'`) y componentes reutilizables con props.
- A unificar la jerarquía visual de toda la aplicación manteniendo una paleta de colores coherente y un diseño limpio tipo dashboard.

## Respuesta a la pregunta de comprensión
¿Qué decisiones visuales has tomado por tu cuenta y qué conceptos de ejercicios anteriores has recuperado?

Respuesta:
He mantenido la coherencia visual aplicando el fondo general oscuro (`#1e293b`) utilizado en los ejercicios anteriores para darle un aspecto moderno. Como conceptos recuperados, he reutilizado las cuadrículas de dos columnas (`flexWrap` y ancho del 48%) vistas en los dashboards y catálogos, la estructura de tarjetas contenedoras con esquinas redondeadas (`borderRadius` y `padding`), y la creación de componentes modulares reutilizables para las estadísticas y las actividades recientes.

## Qué he modificado
- He estructurado una pantalla completa de seguimiento de actividad física que incluye un saludo inicial, una tarjeta de objetivos diarios con barra de progreso, un resumen de métricas en cuadrícula con iconos, y un listado de actividades recientes.
- He adaptado los colores de las tarjetas y los textos para asegurar un buen contraste sobre el fondo oscuro general de la aplicación.

## Resultado
La interfaz muestra un panel de fitness completo, organizado y visualmente atractivo, que integra perfectamente el progreso de pasos diarios, un resumen de métricas clave (calorías, tiempo, pulsaciones y distancia) y un registro de actividades recientes.