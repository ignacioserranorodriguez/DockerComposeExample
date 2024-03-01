REQUISITOS
1. Tener docker-compose funcionando correctamente.
2. Tener cuenta en Docker hub e iniciar sesión.

INSTALACIÓN
1. Descargar el fichero .yml
2. Aplicar el comando "docker-compose docker-compose-a63.yml up" en el directorio donde se encuentre el fichero .yml.
3. Acceder en el navegador a la ruta localhost:8080.
4. Llegar al apartado de conexión con la Base de Datos e introducir los datos que se encuentran en el .yml entre las líneas 31 y 34. 
5. Para el Database Host hay que aplicar el comando "docker inspect bd" con el fin de obtener la IPAddress que usuaremos junto con el puerto 3306 para hacer conexión con el servicio de MariaDB. 