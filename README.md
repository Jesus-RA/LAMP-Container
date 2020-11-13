# Base de docker para proyectos en LAMP 

> Contenedor LAMP de Docker, con todas las configuraciones necesarias para montar un entorno funcional con, php 7.2, mysql 5.5 y phpmyadmin.

Basado en otro repositorio [sprintcube/docker-compose-lamp](https://github.com/sprintcube/docker-compose-lamp)

#### Se usa Docker y Docker-compose

> Con la terminal sobre la carpeta del proyecto poner docker-compose up -d para instalar el contenedor
y levantarlo

` docker-compose up -d `

> Una vez instalado el contenedor para poder entrar en la terminal del contenedor poner el siguiente comando
` docker exec -it 'container-name' bash `

> en mi caso sería
` docker exec -it 7.2-PHP bash `


> Para poder ver todos los contenedores utilizamos el comando
` docker-compose ps `

#### Versiones

- mysql:5.5
- php:7.2-apache-stretch
- phpMyAdmin