# Pedido o Compra

* Cualquier usuario sin autentificar puede registrar un pedido o compra, pero no lo puede finalizar hasta autentificarse como usuario cliente del sistema.
* Se debe poder agregar varios productos asociados a un mismo pedido.
* En cada línea que represente el pedido de un producto se debe poder indicar la cantidad que se solicita.
* Antes de proceder a finalizar y formalizar el pedido se debe presentar un resumen del pedido. 
* Se debe validar las entradas del registro del pedido.
* El pedido debe estar asociado a un cliente.
* **Resumen del pedido:** Se debe presentar cada línea y su subtotal correspondiente y total a pagar de todo el pedido.
* Una vez formalizado el pedido se debe guardar el pedido con la información indicada.



### **Detalle de pedidos o compras para el cliente:**

* Cada usuario cliente debe poder ver una lista de los pedidos que ha realizado, con la información más relevante de cada uno.

* Debe presentar los pedidos correspondientes al usuario que se encuentra autentificado.

## Tabla Pedido

| Campo              | Tipo                  |
| ------------------ | --------------------- |
| ID                 | String(autonumerico)  |
| id_usuario         | fk_id_usuario         |
| id_producto_pedido | fk_id_producto_pedido |
| subtotal           | float                 |
| fecha              | datetime              |
| impuesto_venta     | float                 |
| total              | float                 |

## Tabla Producto_Pedido

| Campo       | Tipo              |
| ----------- | ----------------- |
| ID          | Int(autonumerico) |
| id_producto | fk_id_producto    |
| cantidad    | int               |
| precio      | float             |
| fecha       | datetime          |

