![image](https://github.com/user-attachments/assets/f2beaa73-bd69-4b32-84c7-de638c0b7d30)
![image](https://github.com/user-attachments/assets/ef43c6ce-95ea-4748-bd6d-79ad09f21b3d)

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
