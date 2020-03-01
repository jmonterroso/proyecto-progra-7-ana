# Usuarios

1. Se debe validar las entradas del registro de usuario.
2. Solo el usuario dueño de la cuenta puede ver y actualizar la contraseña.
3. El usuario se puede autentificación con las credenciales de correo y contraseña, se verifica su registro en la aplicación y los recursos a los cuales tiene acceso.
4. Debe presentar la información del usuario que se encuentra autentificado

## Tipo 

### Cliente	

1. El cliente puede registrarse por si solo	

### Administrador

1.  El administrador también puede registrar clientes
2. Lista de usuarios de tipo Cliente, con la información mas relevante

## Clase Usuario



## Tabla Usuario



| Variable        | Tipo              |
| --------------- | ----------------- |
| id              | int(autonumerico) |
| email           | string            |
| password        | string            |
| Nombre          | String            |
| Apellido        | String            |
| EsAdministrator | Boolean           |
| TipoCliente     | String            |
| FechaCreacion   | Datetime(auto)    |



### Layout Examples

#### Registro

https://bootsnipp.com/snippets/0BVEA

#### Login

https://getbootstrap.com/docs/4.4/examples/sign-in/