<h1 align="center"> CRUD Basico con JAVA Y MySQL </h1>
<br>
<p>
        Este uno de mis primeros proyectos personales que realice para generar mi primer CRUD con el lenguaje JAVA y MySQL. <br><br>
        Este es un proyecto personal que me ayudo a poner a prueba mis habilidades de programacion basica:  
    </p>
    <H3 color="red">Pasos ejecutar el proyecto</H3>
    <ol>
        <li>Descarga el proyecto o clonalo en tu ordenador</li>
        <li>Utiliza el entorno de desarrollo de Eclipse para abrir el proyecto</li>
        <li>Para este ejercicio he utlizado el paquete de Xampp como servidor web local que ya viene con un gestor de BBDD MySQL</li>
        <ol TYPE="i">
            <li>Abrimos Xampp</li>
            <li>Ejecutamos los modulos de Apache y MySQL</li>
            <li>Ejecutamos el administrador de MySQL y esperamos que abrab phpMyAdmin en nuestro navegador</li>
            <li>Creamos una nueva BBDD y la tenemos que llamar conexion_end</li>
            <li>Finalmente seleccionamos esa BBDD creada e importamos nuestra BBDD conexion_end.sql</li>
        </ol>
        <li>Volvemos al IDE Eclipse y ejecutamos el archivo conctar.java</li>
    </ol>
    <h3>Nota importante</h3>
    <p>Puede ser que que al momento de ejecutar el proyecto este no ejecute debido a que le hace falta el driver de <strong>mysql-connector-5.1.23-bir.jar</strong> si este es tu caso realiza los siguientes pasos:</p>
    <ol>
        <li>Revisar que tengamos importado nuestro driver mysql-connector-5.1.23-bir.jar en nuestro proyecto para esto :</li>
        <ol TYPE="i">
            <li>Dentro del IDE de eclipse dirígete a la carpeta del proyecto y revisa si hay una equis (x) en rojo</li>
            <li>Haz clic derecho sobre la carpeta principal del proyecto selecciona la opción Build Path y luego selecciona la opción Configure Build Path</li>
            <li>Dirígete a la pestaña de Libreries y luego has click sobre Classpath y se habilitara el la parte derecha el boton de Add External JARs</li>
            <li>Se abrira nuestro panel de rutas de nuestro sistema operativo</li>
            <li>Vamos a buscar nuestro mysql-connector-5.1.23-bir.jar donde hayamos descargado el proyecto o donde lo hayamos clonado y lo vamos a seleccionar</li>
            <li>Final mente podemos dar clic sobre el boton Apply and Cloes</li>
        </ol>
    </ol>
