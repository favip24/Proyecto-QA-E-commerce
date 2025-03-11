# Defecto 01: Mensaje de Error en Usuario Bloqueado No Se Muestra Correctamente #

*Descripción:*
- Cuando un usuario bloqueado intenta iniciar sesión, el mensaje de error "Epic sadface: Sorry, this user has been locked out" no se muestra correctamente.

*Pasos para Reproducir:*
1. Ir a https://www.saucedemo.com/.
2. Ingresar "locked_out_user" y la contraseña "secret_sauce".
3. Hacer clic en "Login".

*Resultado Esperado:*
- El mensaje de error debe mostrarse claramente en pantalla.

*Resultado Observado:*
- El mensaje aparece cortado y parcialmente visible.

*Severidad:* 
- Media

*Prioridad:*
- Alta

# Defecto 02: El Contador del Carrito No Se Actualiza #

*Descripción:*
- Cuando un usuario agrega un producto al carrito, el contador en el ícono del carrito no se actualiza automáticamente.

*Pasos para Reproducir:*
1. Iniciar sesión en SauceDemo.
2. Agregar cualquier producto al carrito.

*Resultado Esperado:*
- El contador del carrito debe aumentar en 1 por cada producto agregado.

*Resultado Observado:*
- El contador no cambia hasta que el usuario refresca la página.

*Severidad:* 
- Alta

*Prioridad:*
- Alta