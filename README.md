# Laboratorio: Formularios de Signup y Login

## Descripción del Proyecto
Este laboratorio consistió en el desarrollo de formularios de registro y autenticación de usuarios para una aplicación móvil enfocada en la "Plataforma para priorización de propuestas de proyectos de gestión del espacio público". Se implementaron las funcionalidades necesarias para garantizar un registro seguro y una autenticación eficiente.

---

## Desarrollo Realizado

### 1. Formulario de Registro
Se implementó un formulario de registro con los siguientes elementos:

- **Nombre completo:** Campo de texto utilizando `TextInputLayout`.
- **Usuario:** Campo de texto utilizando `TextInputLayout`.
- **Correo Electrónico (eMail):** Campo de texto utilizando `TextInputLayout` con validación de formato de email.
- **Dirección física:** Se integró Google Maps API para capturar la ubicación mediante latitud y longitud.
- **Contraseña y confirmación:** Dos campos de texto con `TextInputLayout`, validando coincidencia de contraseñas.
- **Rol del usuario:** Uso de un `Spinner` para seleccionar entre Ciudadano, Planeador o Decisor.
- **Fecha de nacimiento:** Se implementó un `DatePicker` con validación para solo aceptar mayores de 18 años.
- **Género:** Se incluyó un `RadioGroup` con opciones: Masculino, Femenino y Binario.
- **Botón de registro:** Para enviar los datos y crear un nuevo usuario.

### 2. Formulario de Login
Se desarrolló un formulario de autenticación con los siguientes elementos:

- **Usuario:** Campo de texto utilizando `TextInputLayout`.
- **Contraseña:** Campo de texto utilizando `TextInputLayout` con opción de mostrar/ocultar contraseña.
- **Botón de login:** Para validar credenciales y acceder a la aplicación.
- **Botón de registro:** Para redirigir al formulario de signup.

Además, se configuró el formulario de login como la pantalla principal al iniciar la aplicación.

---

## Tecnologías Utilizadas
- **Android Studio** como entorno de desarrollo.
- **Material Design (com.google.android.material)** para los componentes de UI.
- **Google Maps API** para la obtención de la dirección física.
- **Firebase Authentication** (opcional) para la autenticación segura de usuarios.

---
