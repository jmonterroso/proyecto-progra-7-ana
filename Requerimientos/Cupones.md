# Registro de cupones:

* Los cupones los registra el administrador, cada cupón debe estar:
  * asociado a un producto y a un nivel de cliente.

* Los cupones representan descuentos o regalías, entre más alto es el nivel mayor debe ser mayor la retribución al cliente.

* La información que debe cada cupón tener un nombre y descripción, además de la cantidad que se le ofrecerá, según sus características.

* Debe contar con tres diferentes cupones registrados

## **Detalle de cupones:**

* El cliente debe poder visualizar los cupones que tiene cada nivel asignados.
* Además, de los cupones que tiene acceso o que le pertenecen al usuario que esta autentificado.
* Cada cupón que le pertenezca a un usuario cliente debe poder identificarse únicamente por un código.



## **Canjeo de cupones:**

* El administrador se encarga de registrar de canje de cupones, para poder hacer uso de los cupones asignados a cada usuario cliente.

* Debe poder buscarse el usuario cliente, por su correo, para registrar el canje del cupón correspondiente, el cual no debe aparecer como disponible para el cliente.

* El cliente puede ver un detalle del registro del canje



## Tabla Cupones

| Campo           | Tipo                 |
| --------------- | -------------------- |
| ID              | Int(autonumerioc)    |
| Nombre          | String               |
| Descripcion     | String               |
| **Cantidad**    | **Int ❓**            |
| **id_producto** | **fk_id_producto** ❓ |
| id_nivel        | fk_id_nivel          |



