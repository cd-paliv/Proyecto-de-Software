# Proyecto de Software 2022

Web application created for a sports club, developed in Python with [Flask](https://flask.palletsprojects.com/en/2.2.x/) and Vue 3 with [ViteJS](https://vitejs.dev/) for the subject [Proyecto de Software 2022](https://www.info.unlp.edu.ar/wp-content/uploads/2022/03/Proyecto-de-Software.pdf) of the Facultad de Informática, UNLP.  

<p align="center">
   <a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/g2bFsCGp/flaskyvuejs-removebg-preview.png' border='0' alt='Image with Flask y Vue3 logos'/></a>
</p>
A private application was made for the internal management of the data present in the database, and a public app for both employees and club members to use. In addition, based on the finished application, a PWA (Progressive Web Application) was implemented with the [vite-pwa-plugin](https://vite-pwa-org.netlify.app/) library.  

## Tech Stack
  - Python 3.10.x
  - Poetry
  - Flask
  - Vue 3
  - PostgreSQL 13  
  
To see all used libraries in Python: `cd admin; poetry show;`  
To see all used libraries in Vue: `cd portal; npm list;`  

## How to use?
The private application is located inside the *admin* folder, the public application inside the *portal* folder.  
For the public application to run, the private application must be running. It is advisable to have a terminal for each.  

For private application execution: `cd admin; poetry shell; flask --debug run;`  
For private application execution: `cd portal; npm run dev;`

## Contact
  - paulavaccaro1@gmail.com
