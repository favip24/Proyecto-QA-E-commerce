# 1️⃣: Registro y Login de Usuario #

*Descripción:*
- Como usuario, quiero iniciar sesión en la tienda online, para poder realizar compras.

*Criterios de Aceptación:*
- El usuario debe poder iniciar sesión con credenciales válidas.
- Si las credenciales son incorrectas, se debe mostrar un mensaje de error.
- Diferentes tipos de usuarios deben poder acceder correctamente (standard_user, locked_out_user, problem_user, performance_glitch_user).

# 2️⃣: Búsqueda y Filtrado de Productos #

*Descripción:*
- Como usuario, quiero ver los productos disponibles y ordenarlos según precio o nombre, para encontrar lo que necesito más rápido.

*Criterios de Aceptación:*
- Debe haber una lista de productos disponibles.
- El usuario debe poder ordenar productos por "Nombre" y "Precio" (ascendente/descendente).
- Los resultados deben actualizarse correctamente al aplicar un orden.

# 3️⃣: Agregar Productos al Carrito #

*Descripción:*
- Como usuario, quiero agregar productos al carrito, para poder comprarlos posteriormente.

*Criterios de Aceptación:*
- Al hacer clic en "Add to cart", el producto debe aparecer en el carrito.
- Se debe actualizar el número de productos en el ícono del carrito.
- Se debe permitir agregar y eliminar productos del carrito.

# 4️⃣: Proceso de Compra y Pago #
*Descripción:*
- Como usuario, quiero completar el proceso de compra para recibir mis productos.

*Criterios de Aceptación:*
- Debe haber una página de "Checkout" con el resumen de la compra.
- Se deben validar los datos personales antes de finalizar la compra.
- Al completar la compra, debe mostrarse un mensaje de confirmación: "Thank you for your order!".