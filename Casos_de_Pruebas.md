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

# 8️⃣: Validación de Elementos en la UI #

*Precondiciones:*
- El usuario debe tener acceso a la plataforma SauceDemo.

*Pasos:*
1. Iniciar sesión en SauceDemo.
2. Verificar que los botones, imágenes y etiquetas están alineados correctamente.
3. Comprobar que los textos son legibles sin necesidad de hacer zoom.
4. Pasar el cursor sobre los botones y verificar que tienen retroalimentación visual.
5. Verificar que no hay elementos superpuestos o fuera de lugar en la pantalla.

*Resultado Esperado:*
- Todos los elementos están bien alineados y son legibles y no hay elementos desorganizados o fuera de lugar.

# 9️⃣: Verificación de Responsividad #

*Precondiciones:*
- Acceder a SauceDemo en distintos dispositivos o utilizar herramientas de desarrollo para simular resoluciones.

*Pasos:*
1. Abrir SauceDemo en una computadora de escritorio y verificar la alineación de los elementos.
2. Cambiar el tamaño de la ventana y observar si la interfaz se ajusta correctamente.
3. Acceder a SauceDemo desde un dispositivo móvil o simulador.
4. Verificar que no haya elementos desbordados o superpuestos.
5. Probar la funcionalidad de botones y formularios en móviles.

*Resultado Esperado:*
- La interfaz se ajusta correctamente en cada resolución y no hay elementos desbordados ni ocultos en dispositivos pequeños.

# 🔟: Compatibilidad en Diferentes Navegadores #

*Precondiciones:*
- Tener acceso a múltiples navegadores (Chrome, Firefox, Brave, Edge).

*Pasos:*
1. Abrir SauceDemo en Google Chrome y navegar por todas las secciones.
2. Repetir el proceso en Mozilla Firefox.
3. Repetir el proceso en Microsoft Edge.
4. Repetir el proceso en Safari (en caso de tener acceso a Mac).
5. Comparar el diseño, funcionalidad y rendimiento en cada navegador.
6. Documentar cualquier anomalía detectada (errores de renderizado, problemas de carga, fallos en botones, etc.).

*Resultado Esperado:*
- La plataforma carga correctamente en todos los navegadores probados y todas las opciones y botones funcionan de la misma manera en cada navegador.