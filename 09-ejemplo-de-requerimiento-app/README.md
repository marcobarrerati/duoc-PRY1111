[Volver](../README.md)
# App´s
## Requerimientos Funcionales
1. Login de Usuario
1. Recuperar Clave
1. Modificar Clave
1. Registrar Datos
1. Modificar Datos
1. Cerrar Sesión

## Requerimiento y caso de uso pre determinado
### Acceso de usuario
#### Flujo normal
- 1- Usuario ingresa RUN y Contraseña
- 2- Sistema consulta a servicio web
- 3- Servicio web retorna JWT
#### Flujo alterno
- 1- Usuario solicita recuperar cuenta
- 2- Utilizar datos offline para validar acceso
#### Excepciones
- 2.1- Error de conexión
- 2.2- Usuario no existe
- 3- Servicio web rechaza credenciales