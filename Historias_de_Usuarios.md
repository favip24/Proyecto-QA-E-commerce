# 1️⃣: Inicio de Sesión de Usuario #

*Descripción:*
- Como usuario registrado, quiero poder iniciar sesión en la tienda online, para poder realizar compras.

*Criterios de Aceptación:*
- El usuario debe poder iniciar sesión con credenciales válidas.
- Si las credenciales son incorrectas, se debe mostrar un mensaje de error.
- Diferentes tipos de usuarios deben poder acceder correctamente 

# 2️⃣: Cierre de Sesión de Usuario #

*Descripción:*
- Como usuario registrado, quiero poder cerrar sesión para finalizar mi sesión de manera segura y evitar accesos no autorizados a mi cuenta.

*Criterios de Aceptación:*
- Al hacer clic en "Log out", el usuario debe ser redirigido a la pantalla de inicio de sesión.
- La sesión debe cerrarse correctamente y no permitir volver atrás con el navegador.
- No debe quedar información de la cuenta visible tras cerrar sesión.

# 3️⃣: Agregar Productos al Carrito #

*Descripción:*
- Como usuario, quiero poder eliminar productos del carrito de compras para modificar mi selección antes de realizar la compra.

*Criterios de Aceptación:*
- Debe existir un botón para eliminar productos en la vista del carrito.
- Al eliminar un producto, este debe desaparecer de la lista en tiempo real.
- El número de productos en el ícono del carrito debe actualizarse correctamente.

# 4️⃣: Quitar Productos al Carrito #

*Descripción:*
- Como usuario, quiero agregar productos al carrito, para poder comprarlos posteriormente.

*Criterios de Aceptación:*
- Al hacer clic en "Add to cart", el producto debe aparecer en el carrito.
- Se debe actualizar el número de productos en el ícono del carrito.
- Se debe permitir agregar y eliminar productos del carrito.

# 5️⃣: Búsqueda y Filtrado de Productos #

*Descripción:*
- Como usuario, quiero ver los productos disponibles y ordenarlos según precio o nombre, para encontrar lo que necesito más rápido.

*Criterios de Aceptación:*
- Debe haber una lista de productos disponibles.
- El usuario debe poder ordenar productos por "Nombre" y "Precio" (ascendente/descendente).
- Los resultados deben actualizarse correctamente al aplicar un orden.

# 6️⃣: Proceso de Compra y Pago #

*Descripción:*
- Como usuario, quiero completar el proceso de compra para recibir mis productos.

*Criterios de Aceptación:*
- Debe haber una página de "Checkout" con el resumen de la compra.
- Se deben validar los datos personales antes de finalizar la compra.
- Al completar la compra, debe mostrarse un mensaje de confirmación: "Thank you for your order!".

# 7️⃣: Validación de Elementos en la UI #

*Descripción:*
- Como usuario, quiero que todos los elementos de la interfaz sean visibles y accesibles para poder interactuar fácilmente con la plataforma.

*Criterios de Aceptación:*
- Todos los botones, campos de entrada y etiquetas deben estar visibles y alineados correctamente.
- El tamaño del texto y los íconos deben ser legibles en diferentes dispositivos.
- Los botones deben ser interactivos y mostrar retroalimentación al pasar el cursor.
- No deben existir elementos superpuestos o desalineados.

# 8️⃣: Verificación de Responsividad #

*Descripción:*
- Como usuario, quiero que la plataforma se adapte correctamente a distintos dispositivos para una experiencia fluida en móviles, tablets y computadoras.

*Criterios de Aceptación:*
- La página debe ajustarse correctamente en pantallas de diferentes tamaños.
- No debe haber desbordes ni elementos ocultos en dispositivos móviles.
- Los botones y enlaces deben ser accesibles y funcionales en todas las resoluciones.

# 9️⃣: Compatibilidad en Diferentes Navegadores #

*Descripción:*
- Como usuario, quiero que la plataforma funcione correctamente en diferentes navegadores para poder acceder sin problemas desde cualquier opción disponible.

*Criterios de Aceptación:*
- SauceDemo debe funcionar sin errores en los principales navegadores: Chrome, Firefox, Brave, Edge.
- No deben presentarse problemas de renderizado en ningún navegador compatible.
- Todas las funcionalidades deben ser accesibles y operativas en cada navegador.
- Las diferencias visuales entre navegadores deben ser mínimas o inexistentes.