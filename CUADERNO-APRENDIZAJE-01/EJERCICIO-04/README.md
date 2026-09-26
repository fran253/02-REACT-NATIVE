# Ejercicio 04 - Pantalla de acceso

## Qué he aprendido
- A utilizar el componente `TextInput` para incorporar campos de entrada de texto interactivos en la interfaz.
- A aplicar la propiedad `secureTextEntry` para ocultar los caracteres en campos de contraseñas.
- A usar el componente `Pressable` junto a estilos personalizados para simular un botón de inicio de sesión.

## Respuesta a la pregunta de comprensión
¿Por qué en este ejercicio no necesitamos todavía `useState`?

Respuesta:
Porque en esta fase nos estamos centrando únicamente en el diseño visual de la interfaz. No necesitamos almacenar ni procesar el texto que el usuario escribe en los inputs todavia, eso se añadirá más adelante cuando introduzcamos la lógica de la aplicación.

## Qué he modificado
- He adaptado la tarjeta para mantener el fondo oscuro general (`#1e293b`) con la tarjeta en blanco y bordes redondeados.
- He añadido un texto adicional al final (`¿No tienes cuenta? Regístrate`) para completar la estructura visual de la pantalla de acceso.
- He añadido una card para distinguirla del fondo y redondeado los bordes con border radius.

## Resultado
La interfaz muestra una tarjeta centrada con su título y subtítulo, dos campos de entrada (correo y contraseña protegida), un botón azul de inicio de sesión y un texto inferior de registro.