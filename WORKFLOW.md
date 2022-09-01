Flujo de trabajo para desarrollar aplicaciones basadas en contenedores Docker.

Cada contenedor (una instancia de una imagen de Docker) incluye los siguientes componentes:

-Una selección de sistema operativo, por ejemplo, una distribución de Linux, Windows Nano Server o Windows Server Core.
-Archivos agregados durante el desarrollo, por ejemplo, código fuente y binarios de aplicaciones.
-Información de configuración, como la configuración del entorno y las dependencias.

Para poder crear aplicaciones en contenedores de manera simple, consta de los siguientes pasos:

Paso 1. Comience a codificar y cree su aplicación inicial o línea base de servicio.

El desarrollo de una aplicación Docker es similar a la forma en que desarrolla una aplicación sin Docker. La diferencia es que mientras desarrolla para Docker, está implementando y probando su aplicación o servicios que se ejecutan dentro de los contenedores de Docker en su entorno local (ya sea una configuración de máquina virtual de Linux por Docker o directamente Windows si usa contenedores de Windows).

Ademas de tener instalada Visual Studio.

![1](https://user-images.githubusercontent.com/101933399/187957934-bb61f46b-7c91-4b09-a922-b0329fe6fbc7.png)

Paso 2. Cree un Dockerfile relacionado con una imagen base de .NET existente.

Necesita un Dockerfile para cada imagen personalizada que desee crear; también necesita un Dockerfile para cada contenedor que se implementará, ya sea que implemente automáticamente desde Visual Studio o manualmente mediante la CLI de Docker (comandos docker run y docker-compose). Si su aplicación contiene un solo servicio personalizado, necesita un solo Dockerfile. Si su aplicación contiene varios servicios (como en una arquitectura de microservicios), necesita un Dockerfile para cada servicio.

El Dockerfile se coloca en la carpeta raíz de su aplicación o servicio. Contiene los comandos que le indican a Docker cómo configurar y ejecutar su aplicación o servicio en un contenedor. Puede crear manualmente un Dockerfile en código y agregarlo a su proyecto junto con sus dependencias de .NET.

Con Visual Studio y sus herramientas para Docker, esta tarea requiere solo unos pocos clics del mouse. Cuando crea un nuevo proyecto en Visual Studio 2022, hay una opción llamada Enable Docker Support.

![2](https://user-images.githubusercontent.com/101933399/187959014-46496691-4e50-4e84-bca2-93dd7ee28ca7.png)

También puede habilitar la compatibilidad con Docker en un proyecto de aplicación web ASP.NET Core existente haciendo clic con el botón derecho en el proyecto en el Explorador de soluciones y seleccionando Agregar > Compatibilidad con Docker...

![3](https://user-images.githubusercontent.com/101933399/187959797-435ab97f-936f-494b-a530-330e84192d61.png)
