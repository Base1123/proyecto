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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css" rel='text/css'>
    <title>Inicio Sesión</title>
</head>
<body>
  
 Escribimos html y seleccionamos html:5 y luego en <title> escribimos el "inicio sesión" con el codigo </title>
    
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
        
        
        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css" rel='text/css'>
    <title>Formulario de registro</title>
</head>
<body>
    <form action="insertarRegistro.php" class="form-register" method="post">
        <h4>Crear Cuenta </h4>
        
 3.- En registro 
       
     
        
   
                                             
                                           
                                             



  
  
