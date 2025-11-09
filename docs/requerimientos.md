# Requerimientos del Sistema — Sistema Docente Web
**Versión:** v0.1.0
**Estado:** En desarrollo inicial
**Descripción:** Los siguientes requerimientos definen el alcance funcional y técnico de la versión v0.1.0 del sistema **Sistema Docente Web**, centrada en la autenticación y gestión básica de usuarios mediante backend en Spring Boot.

## Requerimientos Funcionales

1. El sistema permitirá loguearse por medio de un identificador de usuario y contraseña.  
2. Una vez logueado, el usuario podrá cambiar su contraseña.
3. El sistema distinguirá entre los roles: **Estudiante**, **Docente** y **Administrador**.
4. El sistema mostrará mensajes o respuestas diferentes según el rol del usuario.
5. Los administradores podrán crear, modificar o eliminar cuentas de usuario.
6. El sistema almacenará las contraseñas de forma cifrada.
7. El sistema deberá permitir cerrar sesión de forma segura.
8. El sistema registrará en base de datos los usuarios y sus roles.
9. El sistema verificará que el identificador (cédula) no esté duplicado al crear nuevos usuarios.
10. El sistema registrará la fecha y hora de los intentos de inicio de sesión.

## Requerimientos No Funcionales

1. El identificador de usuario siempre deberá ser la **cédula de identidad**.  
2. El sistema deberá estar desarrollado con **Java 21 (Spring Boot 3.5.7)** y base de datos **PostgreSQL 18**.  
3. El sistema deberá permitir ser ejecutado localmente mediante **Docker Compose**.  
4. Las contraseñas deberán almacenarse utilizando el algoritmo **BCrypt**.  
5. El sistema deberá cumplir una estructura **modelo–servicio–repositorio** con bajo acoplamiento y alta cohesión.  
6. El sistema deberá incluir **pruebas automatizadas (JUnit 5)** para verificar su funcionamiento básico.