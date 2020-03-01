# Productos 

- 9 productos registrados en la BD que pertenezcan a tres diferentes tipos de clasificaciones.
- **Datos Minimos:** nombre, descripción, precio y el tipo de clasificación al que perteneces.



## Lista de productos 

* Debe presentar una lista de productos o servicios que se encuentren registrados, para cualquier usuario que ingrese a la aplicación.
* Cada producto debe contar con el acceso para agregarlo al pedido o compra, desde la lista de productos que se indica anteriormente.
* Se debe poder filtrar la lista de productos por su clasificación.



## Tabla Producto

| Variable           | Tipo               |
| ------------------ | ------------------ |
| ID                 | Int (autonumerico) |
| Nombre             | String             |
| Descripcion        | String/Text        |
| Precio             | Number/Double      |
| Imagen             | String             |
| Ubicación          | String             |
| Lat                | String             |
| Lng                | String             |
| MetrosCuadrado     | String             |
| Tipo Clasificación | FK_Clasificacion   |



## Tabla Clasificacion

| Variable    | Tipo              |
| ----------- | ----------------- |
| ID          | Int(autonumerico) |
| Descripcion | String            |

