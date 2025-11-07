1. Creamos un repositorio en github Odoo-test y lo configuramos con los directorios adecuados
extra-addons

dummy_module

.gitkeep

Docker-compose.yml

Dockerfile

README.md

3. Iniciamos sesion en Render con Github una vez configurado el repositorio en Git-Hub.

4. Le damos a Add new New Postgres y rellenamos los campos de la base de datos .Usuario, contraseña, database y el host. Version gratuita

5. Despues de crear la base de datos le  damos a Add new Web Service y rellenamos los campos. Verificamos que el Docker y que la region este en frankfurt con version gratuita

6. Luego vamos a las variables de entorno del servidor web y las rellenamos con la informacion necesaria del archivo "Docker" del repositorio y de la base de datos con los parametros $PGDATABASE, $PGHOST, $PGUSER y $PGPASSWORD.

7. Le Damos a Deploy y arranca el servidor, tenemos que esperar a que este en el estado "Deployed" o "Live".

8. Por ultimo hacemos con el  manual deploy del servicio entrando en el URL que nos genera https://odoo-tests-1.onrender.com  y con el inicio de sesion ingresando admin en usuario y admin en contraseña te llevaria a la pagina de Odoo conectado a la base de datos 
