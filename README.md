# Principios Solida Java
Principios SOLID aplicados en Java.

## 01-Single Responsability

Contiene:
- Clase UsuarioOld:
   - Contiene mezcaladas el modelo, la logica de autenticacion de usuario y la logica de validacion de roles.
 
- Clase UsuarioNew:
   - Contiene el modelo.

- Clase PermisoServicio
   - Contiene la logica para comprobar el permiso del usuario en el servicio.
 
- Clase IdentificacionServicio
   - Contiene la logica para identificarse en el servicio.
