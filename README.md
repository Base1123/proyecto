# Proyecto Final
Taller De Base De Datos  

Documentación 

1) Crear una tabla entidad llamada usuario con atributos rut, nombre, apellido, email, contraseña. De la entidad "usuario" a la entidad juegos se forma una relación 1:N.

2) Crear otra tabla llamada juegos con los atributos id, nombre, score y están conectadas con un N:N al unirlas al diagrama se creo otra tabla llamada usuario_has_juegos. De la entidad "juegos" a la entidad usuario se forma una relacion 1:N 

1) Crear base de datos

1.- Crear tabla entidad llamada usuario_eliminados y escribimos los atributos la cuales son rut y su tipo de datos es varchar(13), Nombre y su tipo de datos es varchar(30), Apellido y su tipo de datos es varchar(30), Email y su tipo de datos es varchar(45), Fecha y su tipo de datos es (date), Hora y su tipo de datos es (time). y es para que se guarden los datos que se van eliminando 

2.- Crear otra llamada tabla entidad llamada historicos_usuarios y los atributos son rut y su tipo de datos es varchar(13) nombre y su tipo de datos varchar(30), apellido y su tipo de datos varchar(30), email y su tipo de datos es varchar(45), fecha y su tipo de datos es (date), hora y su tipo de datos es (time) es para que se guardar los datos que se registran en usuario

3.- Crear otra tabla llamada usuario, los a conrut y su tipo de datos es varchar(13), nombre y su tipo de datos es varchar(30), apellido y su tipo de datos es varchar(30), contrasena y su tipo de datos es varchar(16) y politicas y su tipo de datos es varchar(30)

4.- Crear otra tabla entidad llamada usuario_has_juegos y sus atributos son usuario_Rut y su tipo de datos varchar(13) y juegos_id_juegos y su tipo de datos es tinyint(4)

5.- Crear otra tabla llamada juegos con atributos son id_juegos y su tipo de datos es tinyint(4), Nombre y su tipo de datos es varchar(56), Score y su tipo de datos es decimal(4.2).


2) Documentación del Proyecto Final De Programación

1.- Lo que hicimos fue crear un mer con entidad llamada usuario y atributos llamada rut, nombre, apellido, email. contrasena y creamos otra tabla llamada juegos con los atributos id, nombrem score y al unirlas con el N:N se creo otra tabla llamada usuario_has_juegos la cual se va poder conectar la entidad y para saber como se relaciona las tablas. 

2.- Al crear la base de datos creamos la entidad llamada usuario_eliminados llamados con nombre rut, nombre, apellido, email, fecha, y creamos otra tabla llamada historicos_usuarios y los atributos son rut, nombre, apellido, email, fecha y hora. y creamos otra tabla entidad llamada usuario, la cual tiene atributos llamadas rut, nombre, apellido, email, contrasena, politicias y otra tabla llamada usuario_has_juegos que tiene atributos llamadas usuario_Rut, juegos_id_juegos y creamos la ultima tabla de entidad llamada juegos y tiene atributos la cual son id_juegos, nombre y score, y cada uno tiene sus tipos de datos.

3) Documentación PHP del Proyecto Final 

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
   
 3.- Luego creamos el archivo landing.php y escribimos el <h1> y el H1 es una etiqueta que se utiliza para identificar aquellas frases que conforman el título principal de un contenido de una página web. y escribimos "BIENVENIDO" la cual es el titulo, y creamos el "Iniciar test" con el codigo type"submit" y al entrar al Iniciar test nos aparecera el formulario del juego, y luego creamos el botton de "Ver juego" la cual nos permitira ver todo tipo de juego la cual queramos.
   
 
 4.- Crear un archivo de ver.juegos.php la cual nos permitira ver la categoria, tipo de jugador, el valor dedicacional jugar, el valor historial personal, valor conocientos externos el valor pericia, y el valor preferencial
   
   if (isset($_POST["Enviar"])){ 
   $valorCategoria = $_POST["ValorCategoria"];
   $valortipodejugador = $_POST["valortipodeJugador"];
   $valordedicacionaljugar = $_POST["valorhistorialpersonal"];
   $valorconocimientosexternos = $_POST["valorConocimientosExternos"];
   $valorpericia = $_POST["valorpericia"];
   $valorPreferenciaPersona = $_POST["valorpreferenciaspersonales;
   
 
 5.- Creamos un achivo de registro.php, la cual crearemos el formulario de registro y luego creamos un codigo la cual permita el crear la cuenta. 
 
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
       
Escribimos el código select la cual os permita seleccionar cualquier tipo de cosas, y escribimos La Categoria y sus opciones que son Accion, Aventura, Conducción, Deportes, Estrategias, Rol Puzzle, Shooter, Simulacion, Vuelo.
Luego creamos el Tipo de Jugador y seleccionamos 4 alternativas la cual queramos escoger y después creamos la opcion Dedicacion a jugar con sus opciones la cual es de 0 a 1 mes, de 1 a 3 meses, de 0 a 1 meses, de 6 a 9 meses y 10 meses o más.

    
</body>
</html>

Utilizamos el codigo que permita crear el rut, y escribimos el "Ingrese su rut", luego creamos el nombre, apellido, el email, y contraseña para que aparezca en pantalla cuando accedamos al registro. 
Luego creamos las politicias la cual nos permita aceptar las condiciones y las politicas. 


6.- Creamos el archivo insertarRegistro.php

include("db.php");

class Registro extends Conexion{
    public $Rut;
    public $Nombre;
    public $Apellido;
    public $Email;
    public $contrasena;
    public $politicas;

a_ Crear la clase registro y hicimos la conexion, creamos la funcion de _construct la cual esta el rut, nombre, apellido, email, contraseña y politicas y también crear insertarRegistro la cual es Rut, Nombre, Apellido, Email, Contraseña, Y Politicas, luego escribimos la  conexion la cual con el INSERT TO ceamaos el usuario, el rut, nombre, apellido, email, contrasena y politicas y por ultimo creamos el registo con el $registro= new registro la cual el $ sirve para estructurar y desplegar una pagina web.


7.- Creamos el archivo test.php y en el mismo le asignamos el valor que tendrá cada opción que el usuario podrá seleccionar, para aquello hacemos uso de lo siguiente: 

 <title>Formulario para jugadores</title>
</head>
<body>
<div class="container container-fluid">
    <div class="row">
        <div class="col col-md-12">
        <h1 class="">Llena este formulario para asignarte un juego</h1>
        <br>
        <form action="verjuego.php" method="POST">
            <select class="form-select" aria-label="Default select example">
                <option selected>Categoria</option>
                <option value="1.00">Accion</option>
                <option value="2.00">Aventura</option>
                <option value="3.00">Conduccion</option>
                <option value="4.00">Deportes</option>
                <option value="5.00">Estrategia</option>
                <option value="6.00">Rol</option>  
                <option value="7.00">Puzzle</option>
                <option value="8.00">Shooter</option>
                <option value="9.00">Simulacion</option>
                <option value="10.00">Vuelo</option>
            </select>


a) Escribimos el codigo select la cual os permita seleccionar cualquier tipo de cosas, y escribimos La Categoria y sus opciones que son Accion, Aventura, Conducción, Deportes, Estrategias, Rol Puzzle, Shooter, Simulacion, Vuelo.
b) Creamos el Tipo de Jugador y seleccionamos 4 alternativas la cual queramos escoger y 
c) Creamos la opcion Dedicacion a jugar con sus opciones la cual es de 0 a 1 mes, de 1 a 3 meses, de 0 a 1 meses, de 6 a 9 meses y 10 meses o más.


8.- Conectamos la base de datos a través del archivo bd.php, usando lo siguiente:
           
     <?php

require_once("config.php");

class Conexion{

    public $conexion_db;

    public function __construct(){
        $this->conexion_db=mysqli_connect(DB_HOST,DB_USER,DB_PASS,DB_NAME);
        if ($this->conexion_db->connect_errno) 
            {
                echo "Fallo al conectar a MySQL: " . $this->conexion_db->connect_error;
                return;
            }
    }
}

?>
           
 Crear  el require_once la cual incluye y evalua el fichero especificado durante la ejecución del script. y creamos conexion con el codigo class, que es para crear clases en php, y luego la funcion con los nombres de host, user, pass, name. luego en el echo escribimos el "fallo al conextar a Mysql" en caso que no funcione nos dara error.
           
           
           
           
 
9.- Crear el archivo config.php
           
     <?php

    define("DB_HOST", "localhost:3306");
    define("DB_USER", "root");
    define("DB_PASS", "");
    define("DB_NAME", "proyecto_2022_");
    define("DB_CHARSET", "utf8");

?>
           
           
La cual el codigo que escribimos es una utilidad de consola que puede permitir obtener la información sobre la configuracion y solo utilizamos el define para definir el localhost, el usuari, la contraseña, el nombre de la base de datos, y el charset.
           
     
     
 10.- Crear las sesiones 
           
     <main class="container p-4">
  <div class="row">
    <div class="col-md-4">
      <!-- MESSAGES -->

      <?php if (isset($_SESSION['message'])) { ?>
      <div class="alert alert-<?= $_SESSION['message_type']?> alert-dismissible fade show" role="alert">
        <?= $_SESSION['message']?>
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <?php session_unset(); } ?>
      
 Crear las sesiones la cual utilizamos como codigo que nos servirá almacenar datos. Nos va a permitir memorizar todos los datos, la visita al sitio web nos va a permitir acceder en cualquier página.

