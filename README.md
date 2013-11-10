#Documentación de la Practica 2#
================================

##¿Que se ha realizado en la practica?##

El principal objetivo de esta práctica es familiarizarse con este tipo de infraestructura virtual que se usa generalmente para dar un acceso limitado a una aplicación o un servicio tal como un servidor web o a un usuario.

Para ello vamos a crear una jaula, instarlar todo lo que nos sea necesario para que nuestra aplicacion web funcione y finalmente añadir la aplicacion web a la jaula, algo similar al ejercicio 3, 4 y 5 de esta unidad.


###Crear la jaula###

Hemos usado el siguiente comando para instalar la version Wheezy de debian con el debootstrap (usado en el ejercicio 3)

<img src=https://dl.dropboxusercontent.com/u/71428812/p2/p2-1.png />

###Instalar Apache###

despues entramos en la jaula:

<img src=https://dl.dropboxusercontent.com/u/71428812/p2/p2-2.png />

e instalamos Apache, que nos hara falta para poner nuestra aplicacion web en funcionamiento:

<img src=https://dl.dropboxusercontent.com/u/71428812/p2/p2-3.png />

###Introducir nuestra aplicación###

Por último arrancamos Apache y añadimos nuestra aplicación web en /var/www (aplicacion en HTML+Javascript que hicimos en la practica uno)

<img src=https://dl.dropboxusercontent.com/u/71428812/p2/p2-4.png />
