# 1️⃣: Agregar Producto al Carrito #

*Precondiciones:*
- Usuario autenticado.

*Pasos:*
1. Desde la página principal, hacer clic en "Add to cart" en cualquier producto.
2. Ir al carrito (ícono en la parte superior derecha).

*Resultado Esperado:*
- El producto aparece en la lista del carrito.

# 2️⃣: Quitar Producto del Carrito #

*Precondiciones:*
- Usuario autenticado.
- El usuario debe haber agregado al menos un producto al carrito.

*Pasos:*
1. Ir a la sección del carrito.
2. Hacer clic en el botón "Remove" del producto agregado.
3. Verificar que el producto desaparece del carrito.
4. Verificar que el número de productos en el ícono del carrito se actualiza.

*Resultado Esperado:*
-  El producto se elimina correctamente del carrito.

# 3️⃣: Completar Compra con Credenciales Válidas #

*Precondiciones:*
- Tener al menos un producto en el carrito.

*Pasos:*
1. Ir al carrito y hacer clic en "Checkout".
2. Ingresar datos de facturación (First Name, Last Name, ZIP Code).
3. Hacer clic en "Continue" y luego en "Finish".

*Resultado Esperado:*
- Se muestra el mensaje: "Thank you for your order!".

# 4️⃣: Completar Compra con Credenciales NO Válidas #

*Precondiciones:*
- Tener al menos un producto en el carrito.

*Pasos:*
1. Ir al carrito y hacer clic en "Checkout".
2. Ingresar datos de facturación (First Name, Last Name, ZIP Code).
3. Hacer clic en "Continue" y luego en "Finish".

*Resultado Esperado:*
- Se muestra el mensaje: "Thank you for your order!".

# 5️⃣: Búsqueda de Productos por Palabras Claves #

*Precondiciones:*
- El usuario debe estar autenticado en la plataforma (si es necesario).
- Debe haber productos en la base de datos con descripciones relevantes.

*Pasos:*
1. Acceder al sitio web o aplicación.
2. Ubicar la barra de búsqueda.
3. Ingresar una palabra clave relacionada con un producto.
4. Presionar la tecla "Enter" o hacer clic en el botón de búsqueda.

*Resultado Esperado:*
- Se muestran productos que contienen la palabra clave en su nombre o descripción.

# 6️⃣: Búsqueda Sin Resultados #

*Precondiciones:*
- El usuario debe estar en la página de búsqueda de productos.
- No debe existir ningún producto que coincida con la palabra clave ingresada.

*Pasos:*
1. Acceder a la barra de búsqueda.
2. Ingresar una palabra clave que no corresponda a ningún producto.
3. Presionar "Enter" o hacer clic en el botón de búsqueda.

*Resultado Esperado:*
- El sistema muestra un mensaje informando que no hay productos disponibles para la búsqueda realizada.

# 7️⃣: Combinación de Filtros #

*Precondiciones:*
- El usuario debe estar en la página de listado de productos.
- Debe haber productos con diferentes categorías, precios y marcas en la base de datos.

*Pasos:*
1. Acceder a la página de búsqueda o catálogo de productos.
2. Aplicar un filtro de categoría.
3. Aplicar un filtro de precio dentro de un rango determinado.
4. Aplicar un filtro por marca.
5. Verificar los productos mostrados.

*Resultado Esperado:*
- Solo se muestran productos que cumplan con todos los filtros seleccionados.

# 8️⃣: Restablecer Filtros #

*Precondiciones:*
- El usuario debe haber aplicado previamente filtros en la búsqueda de productos.

*Pasos:*
1. Ingresar a la página de productos.
2. Aplicar varios filtros (categoría, precio, marca, etc.).
3. Hacer clic en el botón "Restablecer filtros" o similar.
4. Verificar la lista de productos.

*Resultado Esperado:*
- Se eliminan todos los filtros aplicados y se muestran nuevamente todos los productos disponibles en la plataforma.