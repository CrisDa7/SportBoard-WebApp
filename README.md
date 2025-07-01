![Captura desde 2025-07-01 00-46-01](https://github.com/user-attachments/assets/640ef174-e57a-412d-a9ce-9ea5f06b983a)
![Captura desde 2025-07-01 00-46-09](https://github.com/user-attachments/assets/b9ecd1a1-00a6-4eae-a97a-c2844892d8ed)
![Captura desde 2025-07-01 00-46-14](https://github.com/user-attachments/assets/a83441a6-928c-482c-b649-dbc22a59a07d)
![Captura desde 2025-07-01 00-46-22](https://github.com/user-attachments/assets/31df925e-3395-47b7-ab37-4f3016b1a000)
![Captura desde 2025-07-01 00-46-34](https://github.com/user-attachments/assets/4d374b44-f846-4636-a5b0-22000c2ea68f)






# SportBoard App

## Descripción
SportBoard es una aplicación móvil desarrollada en Flutter conectada a un backend Django. Permite a los usuarios registrarse, iniciar sesión, ver juegos, resultados y su perfil deportivo.

## Requisitos
- Flutter 3.x
- Dispositivo Android físico o emulador
- Backend Django corriendo (ver carpeta `sportboard-mobile-app`)

## Instalación y ejecución
1. Instala Flutter siguiendo la guía oficial: https://docs.flutter.dev/get-started/install
2. Clona este repositorio y entra a la carpeta `sportboard_app`:
   ```bash
   cd sportboard_app
   flutter pub get
   ```
3. Conecta tu dispositivo Android o inicia un emulador.
4. Ejecuta la app:
   ```bash
   flutter run
   ```

## Uso
1. **Registrar cuenta:**
   - Pulsa en "¿No tienes cuenta? Registrar" en la pantalla de inicio de sesión.
   - Completa los campos (Nombre, Email, Contraseña) y pulsa "Registrar".
   - El campo "Nombre" debe ser único (no usado antes). Si ya existe, el sistema mostrará un error.
   - Si el registro es exitoso, vuelve a la pantalla de inicio de sesión.
2. **Iniciar sesión:**
   - Ingresa el **nombre** (no el email) y la contraseña que usaste al registrarte.
   - Pulsa "Ingresar" para acceder a la app.

## Problemas comunes
- Si ves un error al registrar o iniciar sesión, revisa que el backend Django esté corriendo y accesible desde tu dispositivo.
- El botón "Registrar" debe crear la cuenta y luego permitirte iniciar sesión con esos datos.
- Si el botón dice "Sign up" o "Log in" y prefieres español, puedes cambiar el texto en el archivo `lib/main.dart`.
- Si el registro falla, asegúrate de que el nombre de usuario no esté repetido y que todos los campos estén completos.

## Cambiar textos a español
Busca en `lib/main.dart` los textos:
- "Sign up" → "Registrar"
- "Log in" → "Ingresar"
- "Create account" → "Crear cuenta"
- "Welcome back" → "Bienvenido/a"
- "Don't have an account? Sign up" → "¿No tienes cuenta? Registrar"

Puedes modificar estos textos para que toda la app esté en español.

## Contacto
Para dudas o soporte, contacta a cristian@ejemplo.com
