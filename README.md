# proyecto
Taller De Base De Datos  

Documentación 

1) Crear una tabla entidad llamada usuario con atributos rut, nombre, apellido, email, contraseña 

2) Crear otra tabla llamada juegos con los atributos id, nombre, score y están conectadas con un N:N al unirlas al diagrama se creo otra tabla llamada usuario_has_juegos 

Crear base de datos

1.- Crear tabla entidad llamada usuario_eliminados y escribimos los atributos la cuales son rut y su tipo de datos es varchar(13), Nombre y su tipo de datos es varchar(30), Apellido y su tipo de datos es varchar(30), Email y su tipo de datos es varchar(45), Fecha y su tipo de datos es (date), Hora y su tipo de datos es (time). y es para que se guarden los datos que se van eliminando 

2.- Crear otra llamada tabla entidad llamada historicos_usuarios y los atributos son rut y su tipo de datos es varchar(13) nombre y su tipo de datos varchar(30), apellido y su tipo de datos varchar(30), email y su tipo de datos es varchar(45), fecha y su tipo de datos es (date), hora y su tipo de datos es (time) es para que se guardar los datos que se registran en usuario

3.- Crear otra tabla llamada usuario, los a conrut y su tipo de datos es varchar(13), nombre y su tipo de datos es varchar(30), apellido y su tipo de datos es varchar(30), contrasena y su tipo de datos es varchar(16) y politicas y su tipo de datos es varchar(30)

4.- Crear otra tabla entidad llamada usuario_has_juegos y sus atributos son usuario_Rut y su tipo de datos varchar(13) y juegos_id_juegos y su tipo de datos es tinyint(4)

5.- Crear otra tabla llamada juegos con atributos son id_juegos y su tipo de datos es tinyint(4), Nombre y su tipo de datos es varchar(56), Score y su tipo de datos es decimal(4.2).


Documentación 

1.- Lo que hicimos fue crear un mer con entidad llamada usuario y atributos llamada rut, nombre, apellido, email. contrasena y creamos otra tabla llamada juegos con los atributos id, nombrem score y al unirlas con el N:N se creo otra tabla llamada usuario_has_juegos la cual se va poder conectar la entidad y para saber como se relaciona las tablas. 

2.- Al crear la base de datos creamos la entidad llamada usuario_eliminados llamados con nombre rut, nombre, apellido, email, fecha, y creamos otra tabla llamada historicos_usuarios y los atributos son rut, nombre, apellido, email, fecha y hora. y creamos otra tabla entidad llamada usuario, la cual tiene atributos llamadas rut, nombre, apellido, email, contrasena, politicias y otra tabla llamada usuario_has_juegos que tiene atributos llamadas usuario_Rut, juegos_id_juegos y creamos la ultima tabla de entidad llamada juegos y tiene atributos la cual son id_juegos, nombre y score, y cada uno tiene sus tipos de datos.

Documentación PHP 

1.- En el primer paso creamos el archivo del Login.php 

   <link rel="stylesheet" href="style.css" rel='text/css'>
    <title>Inicio Sesión</title>
</head>
<body>
    <form  action="validar.php" class="form-register" method="POST">
        <h4>Iniciar Sesion</h4>
        <input class="controls" type="email" name="Email" id="Email" placeholder="Ingrese su correo">
        <input class="controls" type="password" name="contrasena" id="contrasena" placeholder="Ingrese su contraseña">
        <label class="form-check">
        <button type="submit" class="btn btn-danger" >Iniciar sesion</button>
        <br>
        <br>
        <a class="btn btn-primary" formaction="registro.php" role="button">¿Has olvidado la contraseña?</a>
    </form>
        
2.- Luego escribimos el codigo <form action="validad.php" para validar el inicio de sesion luego en <h4> escribimos el iniciar sesion la cual nos permitira iniciar sesion, luego escribimos <input la cual sirve crear controles interactivos, y escribimos el tipo la cual es email, y el nombre, y en placeholder escribimos que "Ingrese su correo" luego creamos otro input y el tipo se llama password y nombre contraseña. y en placeholder la cual sirve para informar al usuario de que debe escribir en un campo en el formulario y escribiremos "Ingrese su contraseña" luego escribimos el codigo <button y escribimos "Iniciar Sesion" luego creamos un formulario de registro.php y escribimos el ¿Has olvidado la contraseña?
        
        
 3.- Creamos un achivo de registro.php, la cual crearemos el formulario de registro y luego creamos un codigo la cual permita el crear la cuenta. 
 
  <input class="controls" type="text" name="Rut" id="Run" placeholder="Ingrese su Rut">
        <input class="controls" type="text" name="Nombre" id="Nombre" placeholder="Ingrese su Nombre">
        <input class="controls" type="text" name="Apellido" id="Apellido" placeholder="Ingrese su Apellidos">
        <input class="controls" type="email" name="Email" id="Email" placeholder="Ingrese un correo">
        <input class="controls" type="password" name="contrasena" id="contrasena" placeholder="Ingrese una contraseña">
        </div>
            <div class="form-check" style="margin:4px 8px 0px 12px">
                <input class="form-check-input" type="checkbox" value="Acepto las politicas y condiciones" name="politicas" id="politicas" required>
                    <label class="form-check-label" for="flexCheckIndeterminate" style="margin: 0px 0px 0px 3px" required>
                        Acepta las condiciones y politicas de uso
                    </label>
            </div><br>
        <button type="submit" name="registrar" class="btn btn-danger" >Registrar</button>
        <br>
        <p><a href="login.php">¿Ya tengo cuenta?</a></p>

    </form>

    
</body>
</html>


4.- Luego utilizamos el codigo que permita crear el rut, y escribimos el "Ingrese su rut", luego creamos el nombre, apellido, el email, y contraseña para que aparezca en pantalla cuando accedamos al registro. 
Luego creamos las politicias la cual nos permita aceptar las condiciones y las politicas. 

<form action="test.php" method="post">
    <h1>BIENVENIDO</h1>
    <div class="d-grid gap-2 col-6 mx-auto">
        <button class="btn btn-primary" type="submit">Iniciar Test</button>
    </div>
</form>
<br>
<br>
<form action="verjuego.php" method="post">
    <div class="d-grid gap-2 col-6 mx-auto">
        <button class="btn btn-primary" type="submit">Ver Juego</button>
    </div>

       
     
        
   
                                             
                                           
                                             



  
  
