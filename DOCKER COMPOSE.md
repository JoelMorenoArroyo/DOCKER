El uso de Compose es básicamente un proceso de tres pasos:

    Defina el entorno de su aplicación con un Dockerfilepara que pueda reproducirse en cualquier lugar.

    Defina los servicios que componen su aplicación docker-compose.yml para que puedan ejecutarse juntos en un entorno aislado.

    Ejecutar docker compose upy el comando de redacción de Docker se inicia y ejecuta toda su aplicación. 
    Alternativamente, puede ejecutar docker-compose upusando Compose standalone ( docker-composebinario).

Un docker-compose.ymlse parece a esto:

    version: "3.9"  # optional since v1.27.0
      services:
      web:
        build: .
        ports:
          - "8000:5000"
        volumes:
          - .:/code
          - logvolume01:/var/log
        depends_on:
          - redis
      redis:
        image: redis
      volumes:
        logvolume01: {}

Realizando el paso a paso de la conformación del docker compose este es el avance:

![Screenshot_1](https://user-images.githubusercontent.com/101933399/188924073-03b66fec-11c1-474b-bfbc-d5bf78ab7f26.jpg)

![Screenshot_2](https://user-images.githubusercontent.com/101933399/188924088-d2229ca7-a023-43d2-be10-8194b63324a1.jpg)

![Screenshot_3](https://user-images.githubusercontent.com/101933399/188924110-3f019056-272a-4b47-af0f-7e369bd25a10.jpg)

![Screenshot_4](https://user-images.githubusercontent.com/101933399/188924125-a85f7147-72fa-4816-abf9-6448637d7d6e.jpg)

![Screenshot_5](https://user-images.githubusercontent.com/101933399/188924141-99b8195f-2abd-49e2-9ebe-0f7187ed4642.jpg)

![Screenshot_6](https://user-images.githubusercontent.com/101933399/188924153-205958c1-9acb-43c3-914b-c506a91fe897.jpg)

