# 1️⃣: Inicio de Sesión con Credenciales Válidas #

*Precondiciones:* 
- Tener credenciales válidas.

*Pasos:*
1. Ir a [https://www.saucedemo.com/](https://www.saucedemo.com/).
2. Ingresar "standard_user" y la contraseña "secret_sauce".
3. Hacer clic en "Login".

*Resultado Esperado:*
- Se muestra la página principal con la lista de productos.

# 2️⃣: Inicio de Sesión con Credenciales NO Válidas #

*Precondiciones:*
- Usar credenciales de usuario bloqueado.

*Pasos:*
1. Ir a la página de inicio de sesión.
2. Ingresar "locked_out_user" y la contraseña "secret_sauce".
3. Hacer clic en "Login".

*Resultado Esperado:*
- Aparece el mensaje de error: "Epic sadface: Sorry, this user has been locked out".

# 3️⃣: Cierre de Sesión Correctamente #

*Precondiciones:*
- El usuario debe estar autenticado en SauceDemo.

*Pasos:*
1. Hacer clic en el menú de navegación.
2. Seleccionar la opción "Logout".

*Resultado Esperado:*
- El usuario es redirigido a la página de inicio de sesión.

# 3️⃣: Cierre de Sesión de forma Interrumpida #

*Precondiciones:*
- El usuario debe estar autenticado en SauceDemo.

*Pasos:*
1. Hacer clic en el menú de navegación.
2. Seleccionar la opción "Logout".
3. Regresar con el botón "Atrás" del navegador.
3. Cerrar el Navegador con el botón situado en la esquina superior derecha "X"

*Resultado Esperado:*
- El usuario es redirigido a la página de inicio de sesión.
- Al abrir el navegador el usuario es dirigido a la págiuna de inicio de sesión.

# 4️⃣: Agregar Producto al Carrito #

*Precondiciones:*
- Usuario autenticado.

*Pasos:*
1. Desde la página principal, hacer clic en "Add to cart" en cualquier producto.
2. Ir al carrito (ícono en la parte superior derecha).

*Resultado Esperado:*
- El producto aparece en la lista del carrito.

# 5️⃣: Quitar Producto al Carrito #

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

# 6️⃣: Completar Compra con Credenciales Válidas #

*Precondiciones:*
- Tener al menos un producto en el carrito.

*Pasos:*
1. Ir al carrito y hacer clic en "Checkout".
2. Ingresar datos de facturación (First Name, Last Name, ZIP Code).
3. Hacer clic en "Continue" y luego en "Finish".

*Resultado Esperado:*
- Se muestra el mensaje: "Thank you for your order!".

# 7️⃣: Completar Compra con Credenciales NO Válidas #

*Precondiciones:*
- Tener al menos un producto en el carrito.

*Pasos:*
1. Ir al carrito y hacer clic en "Checkout".
2. Ingresar datos de facturación (First Name, Last Name, ZIP Code).
3. Hacer clic en "Continue" y luego en "Finish".

*Resultado Esperado:*
- Se muestra el mensaje: "Thank you for your order!".