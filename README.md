# Proyecto de Software 2022

Aplicación web creada para un club deportivo, desarrollada en Python con [Flask](https://flask.palletsprojects.com/en/2.2.x/) y Vue 3 con [ViteJS](https://vitejs.dev/) para la asignatura [Proyecto de Software 2022](https://www.info.unlp.edu.ar/wp-content/uploads/2022/03/Proyecto-de-Software.pdf) de la Facultad de Informática, UNLP.

<p align="center">
  <img src="https://i.postimg.cc/g2bFsCGp/flaskyvuejs-removebg-preview.png" alt="Imagen con logos de Flask y Vue3">
</p>

Se realizó una aplicación privada para el manejo interno de los datos presentes en la base de datos, y una aplicación pública para que utilicen tanto los empleados como los socios del club. Además, en base a la aplicación finalizada se implementó una PWA (Progressive Web Application) con la librería [vite-pwa-plugin](https://vite-pwa-org.netlify.app/).

Para ver todas las librerías utilizadas en Python: `cd admin; poetry show;`  
Para ver todas las librerías utilizadas en Vue: `cd portal; npm list;`

## Ejecución local
Instalaciones necesarias:  
  - Python 3.10.x
  - Poetry
  - Flask
  - Vue 3
  - PostgreSQL 13

La aplicación privada se encuentra dentro de la carpeta *admin*, la aplicación pública dentro de la carpeta *portal*. 
Es necesario tener instaladas todas las librerías para la ejecución exitosa, por lo que dentro de la carpeta *admin* ejecutar el comando: `poetry shell; poetry install;`, y dentro de la carpeta *portal* ejecutar el comando `npm install`.

Para la ejecución de la aplicación pública, es necesario que se esté ejecutando la aplicación privada. Es recomendable tener una terminal para cada una.

Para la ejecución de la aplicación privada: `cd admin; poetry shell; flask --debug run;`  
Para la ejecución de la aplicación pública: `cd portal; npm run dev;`

## Contacto
  - paulavaccaro1@gmail.com
