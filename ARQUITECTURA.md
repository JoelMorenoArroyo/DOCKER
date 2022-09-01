Maquinas virtuales vs Contenedores.

Antes de empezar con la especificación de los procesos, variables y demas conceptos de los componentes de Docker, cabe resaltar sus ventajas con respecto a lo que anteriormente se realizaba de la virtualización y la agilidad con la que los procesos se realizan ahora con el concepto de contenedores.

![maquinas virtuales](https://user-images.githubusercontent.com/101933399/187817198-8d6f62e9-0c31-4e32-a9af-5aa6a5c7ae56.jpg) ![contenedores](https://user-images.githubusercontent.com/101933399/187817214-96340f04-ece8-4b94-a8cf-b780442ebea6.jpg)

Los componentes de Docker

Docker es una herramienta de desarrollo y un entorno de ejecución. Todo se basa en el concepto de imagen de contenedor. Como esbozamos en nuestro artículo anterior al definir sus componentes, cada contenedor es una instancia de una imagen, y múltiples contenedores a partir de la misma imagen serán completamente idénticos, clones, que tan solo se diferenciarán por la capa de escritura, los datos y archivos que manejen en cada caso en particular.

Cuando se elimina el contenedor, es decir, una instancia determinada, se elimina también esa capa de escritura a menos que se realice un docker commit. Al hacer esto, todo el contenedor, incluida la capa de escritura, se guarda como una nueva imagen de contenedor.

Los componentes principales de Docker son:

Docker Daemon, o Docker Engine, una capa delgada entre los contenedores y el kernel de Linux. Es el entorno de tiempo de ejecución persistente que administra los contenedores de aplicaciones, y es independiente del sistema operativo subyacente, por tanto, cualquier contenedor de Docker puede ejecutarse en cualquier servidor que tenga habilitado este servicio.

![docker-engine-components](https://user-images.githubusercontent.com/101933399/187815986-762e9971-b56f-4355-8fd7-549035cb13d0.png)

Dockerfile es un documento que se utiliza para crear las imágenes de contenedor. Un Dockerfile es un documento de texto que contiene toda la información de configuración y los comandos necesarios para ensamblar una imagen de contenedor. El encargado de convertir un dockerfile en un contenedor es, como se puede imaginar, el Docker Daemon.

Docker dispone además de una interfaz por línea de comandos con múltiples herramientas que permiten controlar el ciclo de vida de los contenedores. Se trata de una lista bastante extensa que cubre una amplia cantidad de órdenes específicas. Gracias a estas herramientas es posible compilar, exportar y etiquetar, o disponer de funciones de tiempo de ejecución como ejecutar, eliminar, iniciar y detener un contenedor, entre otras.

![arquitectura](https://user-images.githubusercontent.com/101933399/187817608-547288d2-574f-4aa0-af79-4923328539c9.jpg)
