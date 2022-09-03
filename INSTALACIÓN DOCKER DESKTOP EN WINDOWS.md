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

 
