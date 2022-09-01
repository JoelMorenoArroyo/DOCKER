Docker Build.

La opción de Docker Build es un comando de la plataforma Docker que se utiliza para la construcción de imágenes desatendidas. En otras palabras, aquella que se encarga de crear imágenes de Docker partiendo de un «contexto» y de un archivo de Dockerfile.

Docker Run.

El comando Docker Run se utiliza para cumplir la función de ejecutar procesos en contenedores aislados.

Docker Start.

Pone en funcionamiento un contenedor que esté parado. Es decir, cuando has creado un contenedor con el comando anterior ( docker create ) puedes ejecutarlo con docker start.

Docker Rmi.

Remueve imágenes por su ID. Para remover la imagen, primero necesitas una lista de todas las imágenes para obtener las IDs de imagen, nombre de la imagen, y otros detalles. Ejecutando un simple comando docker imagenes -a o docker imagenes.

Docker RM.

Es un comando que permite la eliminación de contenedores, imágenes, volúmenes y redes de Docker que estén pendientes.

Este comando es muy importante para el uso de Docker, una plataforma de software para crear apps. ¿Por qué? Esto se debe a que, al trabajar con esta herramienta, el usuario puede acumular de manera muy rápida un extenso número de objetos sin utilizar y que ocupan una gran cantidad de espacio en el disco, saturando así la salida originada por los comandos del sistema. De manera que Docker no se encarga directamente de eliminar todos objetos que la plataforma no usa, a menos que el usuario lo indique de forma explícita a través de la ejecución de comandos como Docker RM y sus diferentes opciones.

Docker stop.

El comando se usa para detener un contenedor en ejecución. Aquí tenemos que poner el nombre o ID del contenedor junto con esto. En caso de éxito, devolvería el nombre o ID de la ventana acoplable. Esto devolverá el CONTAINER ID que puede utilizar para detener el contenedor.

Docker Network RM.

