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

# 3️⃣: Cierre de Sesión Interrumpido #

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