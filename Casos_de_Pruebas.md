# 1️⃣: Inicio de Sesión Exitoso #

*Precondiciones:* 
- Tener credenciales válidas.

*Pasos:*
1. Ir a [https://www.saucedemo.com/](https://www.saucedemo.com/).
2. Ingresar "standard_user" y la contraseña "secret_sauce".
3. Hacer clic en "Login".

*Resultado Esperado:*
- Se muestra la página principal con la lista de productos.

# 2️⃣: Intento de Login con Usuario Bloqueado #

*Precondiciones:*
- Usar credenciales de usuario bloqueado.

*Pasos:*
1. Ir a la página de inicio de sesión.
2. Ingresar "locked_out_user" y la contraseña "secret_sauce".
3. Hacer clic en "Login".

*Resultado Esperado:*
- Aparece el mensaje de error: "Epic sadface: Sorry, this user has been locked out".

# 3️⃣: Agregar Producto al Carrito #

*Precondiciones:*
- Usuario autenticado.

*Pasos:*
1. Desde la página principal, hacer clic en "Add to cart" en cualquier producto.
2. Ir al carrito (ícono en la parte superior derecha).

*Resultado Esperado:*
- El producto aparece en la lista del carrito.

# 4️⃣: Completar Compra #

*Precondiciones:*
- Tener al menos un producto en el carrito.

*Pasos:*
1. Ir al carrito y hacer clic en "Checkout".
2. Ingresar datos de facturación (First Name, Last Name, ZIP Code).
3. Hacer clic en "Continue" y luego en "Finish".

*Resultado Esperado:*
- Se muestra el mensaje: "Thank you for your order!".