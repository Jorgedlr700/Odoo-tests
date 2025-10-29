Iniciamos sesion en Render una vez configurado el repositorio en Git-Hub.
Le damos a Add new Web Service y rellenamos los campos.
Le Damos a Deploy y arranca el servidor, tenemos que esperar a que este en el estado "Deployed" o "Live".
Creamos la base de datos en el apartado + New, ingresando nombre y datos
Vamos a las variables de entorno del servidor web y las rellenamos con la informacion necesaria del archivo "Docker" del repositorio y de la base de datoscon los parametros $PGDATABASE, $PGHOST, $PGUSER y $PGPASSWORD.
Por ultimo hacemos un manual deploy del servicio e iniciando sesion te llevaria a la pagina de Odoo
