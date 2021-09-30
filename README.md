# Automatización de pruebas 

<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn.nohat.cc%2Fthumb%2Ff%2F720%2F6753122949005312.jpg&f=1&nofb=1/200/300" />

Este es un proyecto educacional de Duoc del ramo llamado Automatización de pruebas, el cual recibimos un caso, luego el código de este caso para posteriormente crear pruebas utilizando la metodología TDD (Test Driver Development). Todo esto se realizará en el lenguaje de programación Python.


## Caso nº 2 (Sistema de gestión almacén los “Yuyitos”).


Contexto:

Una señora llamada “Juanita” arrancó con un emprendimiento para ayudar con los gastos en la casa. El emprendimiento consistía en un bazar que ofrecía diversos productos, el éxito de su negocio fue tan grande que incrementó sus ventas hasta un “X3 porciento”.

Por motivos de su crecimiento exponencial, la señora Juanita no estaba preparada para este crecimiento, el cual trajo los siguientes problemas para manejar su inventario, ya sea la existencia actual de productos como la cantidad a comprar de estos.

Juanita nos indica que cada año irá creciendo su negocio, esto es debido a que en la zona que se encuentra no existen supermercados.


Requerimientos:

Juanita a solicitado un sw que funcione dentro de la web, el cual pueda gestionar inventarios usando el código de barra y así facilitar el ingreso y egreso de productos.

Con lo mencionado anteriormente se le solicitó los requerimientos necesarios para poder crear esta app:

-	Registro de proveedores: Debe poder ingresar los datos de proveedores, esto quiere decir que solicitaremos lo siguiente:
o	Nombre.
o	Rut.
o	Persona contacto.
o	Teléfono.
o	Dirección.
o	Rubro.

-	Registro clientes: Debe solicitar los siguientes datos a sus clientes:
o	Rut.
o	Nombre.
o	Apellido.
o	Dirección.
o	Teléfono.
o	Correo.

-	Registro de productos: Debe ingresar productos y almacenarlos:
o	Id producto.
o	Descripción.
o	Precio compra.
o	Precio venta.
o	Marca.
o	Cantidad actual.
o	Código de producto.
Restricciones:

a)	999, los primeros tres dígitos corresponden al ID del Proveedor. 
b)	 999, los tres siguientes dígitos corresponden a la familia del producto, por ejemplo: Aceite, Azúcar, etc. 
c)	 99999999, los siguientes 8 dígitos corresponden a la fecha de vencimiento, si no tienen fecha de vencimiento se debe llenar con ceros. 
d)	999, los siguientes tres dígitos corresponden a un número secuencial que hacen referencia al producto.

-	Registro de los pagos a crédito:  Debemos generar una solicitud para las compras a crédito, SÓLO SON APROBADAS POR LA SR JUANITA.  Esta ficha contendrá lo siguiente:
o	Rut.
o	Nº de boleta.
o	Fecha.
o	Estado (“Pagada”/”Pendiente”).

-	Registro de ventas: Para poder registrar ventas dentro del sw será mediante la impresión de boletas, además se podrá ingresar registrar los productos mediante código de barra o la digitalización del código. Tras realizar el proceso mencionado se actualizará el stock y podrá generar una “ficha de crédito” (si es necesario).

-	Registro de orden de pedido: Debe generar una orden de los pedidos por los proveedores, el cual deberá contener la siguiente información:

o	Fecha.
o	Rut.
o	Código producto.
o	Descripción.
o	Cantidad.
o	Precio.

-	Registro de recepción de productos: En esta sección se visualizará los productos solicitados en la “orden de pedido” y poder generar la recepción de productos para el proveedor.

-	Código de barra: Debe generar código de barras para cada producto y poder imprimirlas.



## License
[MIT](https://choosealicense.com/licenses/mit/)
