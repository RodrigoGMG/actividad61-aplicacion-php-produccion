# Aplicación CRUD php a implantar en el servidor de produccioón

>IES Miguel Herrero (Torrelavega) - Curso 2024/2025
>Módulo: IAW - Implantación de Aplicaciones Web  
>Ciclo: CFGS Administración de Sistemas Informáticos en Red  

Este repositorio es una **guía** para la realización de la **actividad 6.1** de IAW. Contiene lo siguiente: 

* Directorio /sql: Contiene un archivo con un script SQL para la inicialización de la BD de MariaDB
* Archivo .env: Configuración de variables de entorno (Contraseña Root, nombre BD, usuario BD y contraseña BD) utilizadas por el archivo docker-compose.yml para la inicializacion de MariaDB.
* Archivo docker-compose.yml: Modelo escenario de contenedores para el despliegue de la aplicación PHP. Contiene 2 servicios: Ubuntu+apache+PHP+Aplicacion CRUD PHP y Mariadb.


