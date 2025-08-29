# devops-contenedores
practica

REQUISITOS:
-----------
Tener instalado docker, docker-compose.


INSTRUCCIONES:
--------------
Para poder levantar el stack debe seguir los sigueintes pasos:

1.- git clone https://github.com/vicoslo/devops-contenedores.git

2.- cd devops-contenedores/

3.- docker-compose up -d

4.- dirigise a su navegador y colocar http://localhost:3001

5.- Para ingresas a la base de datos los datos de coneccion estan seteados en el docker-compose.yml por el puerto 27018 desde el host local

LOGS:

1.- docker-compose logs -f

2.- docker-compose logs


CRUD
-----
El crud puede ud registar personas con sus datos y url de su imagen, estas son guardads en la base de datos de mongo, al ser dinamico se muestra en la misma pagina, tambien esta la opciones de editar y eliminar.
