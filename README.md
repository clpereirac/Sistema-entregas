# directorios:

```
assets
controllers
model
public
|_ fonts
|  |_ SF-PRO
|_ images
|_ styles
views
```
# 

Registro de usuario e inicio de sesión.
Agregar un nuevo cliente al sistema.
Agregar una nueva entrega al sistema.
Ver todos los clientes en el sistema.
Ver todas las entregas en el sistema.
Busque un cliente específico por su nombre o apellido.
Busque entregas según la fecha de entrega.
Actualizar la información de un cliente.
Actualizar la información de una entrega.
Eliminar un cliente del sistema.
Eliminar una entrega del sistema.
Muestra estadísticas de pedidos diarios y de todos los tiempos.

## 

HTML/CSS para desarrollo frontend.
PHP para desarrollo backend.
Base de datos MySQL para almacenamiento de datos.

## BD

tablas:
1. userTabla que almacena información del usuario, como nombre de usuario, contraseña y correo electrónico.
2. clientTabla que almacena información del cliente, como nombre, apellido, dirección y número de teléfono. Tiene una relación de clave externa con la usertabla.
3. commandeTabla que almacena información de entrega como fecha de entrega, nombre del cliente, cantidad, precio y precio total. Tiene una relación de clave externa con la clienttabla y la usertabla.

