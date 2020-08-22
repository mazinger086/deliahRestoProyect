# deliahRestoProyect

Ultimo proyecto de la Carrera de Fullstack en Acamica

Sobre el codigo que encontraras en este repositorio, se trata de desarrollar una API desde cero, lo cual incluye la creacion y el consumo por el cliente atraves del protocolo HTTP (el cual se puede verificar con la herramienta de Postman). Dentro de la carpeta vista encontraras el copy de los diferentes endpoints y como va trabajando la API en cada peticion.

## Archivos disponibles

#### Modelo de base de datos
DDentro de la carpeta `db` se encuentra el archivo `setup.js` que cuenta con la estructura de la base de datos. También podemos encontrar `insert.js` con algunos datos de ejemplo. Antes de ejecutar el proyecto se recomienda ejecutar `npm run setup` y luego `npm run insert` para realizar las migraciones.

#### Especificación de la API
En el archivo `spec.yaml` se encuentra la especificación de la Api, endpoints y modelo de datos.

#### Vistas
Dentro de la carpeta `views` encontramos las vistas de UI que corresponden a los diferentes flujos y endpoints del proyecto.


## Instrucciones
1- Descargar el repositorio
2- Instalar las dependencias que se indican en el archivo `package.json`.
3- Ejecutar `XAMPP` y activar `Apache` y `MySql`. 
4- Ejecutar desde el terminal npm run setup para crear la base de datos delilah_resto_v1. 
5- Luego de crear la base podes insertar datos con el siguiente script npm run insert. 
6- Ejecutar desde el terminal npm run ini para iniciar el servidor.
7- Testear con Postman el funcionamiento de la API.

## Notas a tener en cuenta
1- Tener instalado `Node.js`  
2- Tener instalado `XAMPP` o algún sistema de gestión de bases de dato MySQL.  
3- Tener instalado `Postman` o cualquier entorno que permita el consumo de la API como cliente HTTP.
