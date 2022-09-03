![maxresdefault (2)](https://user-images.githubusercontent.com/101933399/188052438-68d064c4-e39a-4ee3-a46a-e8ad41640808.jpg)

Proceso de instalación de Docker Desktop en windows y descripción general de los requisitos del sistema.

	-Windows 11 de 64 bits: Home-Pro versión 21H2 o superior, o Enterprise o Education versión 21H2 o superior. 

	-Windows 10 de 64 bits: Home-Pro 21H1 (compilación 19043) o superior, o Enterprise o Educ. 20H2 (compilación 19042) o superior. 

	-Habilite la función WSL 2 en Windows o en su efecto ya tener instalado previamente WSL 2.  

Se requieren los siguientes requisitos previos de hardware para ejecutar correctamente WSL 2 en Windows 10 o Windows 11:

	-Procesador de 64 bits con traducción de direcciones de segundo nivel (SLAT)
	
  	-RAM del sistema de 4GB
	
  	-El soporte de virtualización de hardware a nivel de BIOS debe estar habilitado en la configuración del BIOS.

Descargue e instale el paquete de actualización del kernel de Linux .

	INFORMACIÓN IMPORTANTE
	
	Los contenedores y las imágenes creadas con Docker Desktop se comparten entre todas las cuentas de usuario en las máquinas donde
	está instalado. Esto se debe a que todas las cuentas de Windows usan la misma máquina virtual para crear y ejecutar contenedores. 
	No es posible compartir contenedores e imágenes entre cuentas de usuario cuando se usa el backend Docker Desktop WSL 2.

 DESCARGAR INSTALADOR EJECUTABLE DE DOCKER DESKTOP PARA WINDOWS.
 
 Primero se debe dirigir a la pagina https://docs.docker.com/desktop/install/windows-install/ para descargar el archivo de instalación del programa. Donde les saldra lo siguiente y deb darle clic para descargar.
 
 ![1](https://user-images.githubusercontent.com/101933399/188250812-5ad66533-e8a9-44cb-8759-959201579e78.jpg)

Deben aceptar y guardar el archivo que se va a descargar en su equipo.

![2](https://user-images.githubusercontent.com/101933399/188250824-864101d2-a012-4396-8bc6-c50d421fea98.jpg)

A continuación empezara la descarga, el tiempo estimado dependera de su conexión a internet.

![3](https://user-images.githubusercontent.com/101933399/188250834-3e01b236-4333-4144-830b-e14f0847a12f.jpg)

INSTALACIÓN DE DOCKER.

Despues de haber terminado la descarga del programa procedemos a ejecutar el archivo.

![4](https://user-images.githubusercontent.com/101933399/188250903-a71710e0-4468-4637-9a58-fc07208e2d82.jpg)

![instalacion docker1](https://user-images.githubusercontent.com/101933399/188250915-cf714fad-341a-4efe-be5a-f900ae6f8608.jpg)

![instalacion docker2](https://user-images.githubusercontent.com/101933399/188251019-801516b6-46e1-4e5f-94e4-906037975afb.jpg)

![instalacion docker3](https://user-images.githubusercontent.com/101933399/188251032-a479c438-e518-4b3c-9454-61c80ddbad19.jpg)

![instalacion docker4](https://user-images.githubusercontent.com/101933399/188251037-f74831ca-4520-4799-b549-0881a401b398.jpg)

![instalacion docker5](https://user-images.githubusercontent.com/101933399/188251040-999042fe-d903-492a-9471-e443c2ce205d.jpg)

![instalacion docker6](https://user-images.githubusercontent.com/101933399/188251043-eebaf90d-58a2-4242-b8da-728ff48df5e5.jpg)

