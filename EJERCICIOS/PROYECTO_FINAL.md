# Proyecto Final de base de datos.
### Indicaciones de lo que se debe realizar

● Diseña el modelo entidad-relación del siguiente problema.

● Crea el script para la base de datos.
Proveedores

Tenemos que diseñar una base de datos sobre proveedores y disponemos de
la siguiente información:

● De cada proveedor conocemos su nombre, dirección, ciudad, provincia y
un código de proveedor que será único para cada uno de ellos.

● Nos interesa llevar un control de las piezas que nos suministra cada
proveedor. Es importante conocer la cantidad de las diferentes piezas
que nos suministra y en qué fecha lo hace. Tenga en cuenta que un
mismo proveedor nos puede suministrar una pieza con el mismo código
en diferentes fechas. El diseño de la base de datos debe permitir
almacenar un histórico con todas las fechas y las cantidades que nos ha
proporcionado un proveedor.

● Una misma pieza puede ser suministrada por diferentes proveedores.

● De cada pieza conocemos un código que será único, nombre, color,
precio y categoría.

● Pueden existir varias categorías y para cada categoría hay un nombre y
un código de categoría único.

● Una pieza sólo puede pertenecer a una categoría.


![image](https://user-images.githubusercontent.com/101481188/173170169-f238436d-38ff-42f9-a706-b13c15e16354.png)


![image](https://user-images.githubusercontent.com/101481188/173170187-89e3a066-09b0-41ef-8941-b9fd398e5c28.png)

Mi código SQL:  https://www.db-fiddle.com/f/kMUdz38q2KSusYeURFvnWM/0



