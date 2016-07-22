#Prueba de c�digo

CRUD b�sico de productos. crear, ver, actualizar y borrar.

Los campos necesarios de un producto son:
```
name:string price:integer description:text price_discount:integer
```
##Funcionalidades

* Creaci�n de CRUD

* Los productos tendran paginaci�n

* La creaci�n de los productos solo se podr� hacer si el usuario tiene rol de administrador

* Los productos pueden tener varias im�genes.

* Los productos se podr�n filtrar mostrando solo los productos en promoci�n, tambi�n se pueden ordenar seg�n el precio de manera ascendente o descendente.

* El administrador podr� descargar un csv con todos los productos.

##Requerimientos

Cada vez que se termine una funcionalidad debe estar en una rama aparte o con un git tag.

Se usara Bootstrap como framework de css y js; todas las vistas deben ser lo mas simple posible.

Para la suit de test se usara Rspec y FactoryGirl; deben escribirse todos los test necesarios para probar que el CRUD funciona correctamente.
cualquier metodo que se escriba en el modelo debe tener su correspondiente test unitario, cualquier variable que se asigne en el controlador debe tener un test unitario que comprueba el valor de esa variable. (recomendado usar scaffold y ver los test de CRUD creados por rspec)

Se debe proporcionar una seed de la base de datos con 10000 records y todos los test deben pasar.
