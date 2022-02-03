# Practica_obligatoria2
# Fernan Tickets
Fernan Tickets es un programa para gestionar los tickets de incidencias que los usuarios abren.

## Manual de Usuario



**Indice**
 ### 1.Manual de usuario.<br>
  #### &nbsp; &nbsp; 1.1 Menu principal.<br>
  #### &nbsp; &nbsp; 1.2 Usuario Básico<br>
  #### &nbsp; &nbsp; 1.3 Usuario Técnico<br>
  #### &nbsp; &nbsp; 1.4 Usuario Administrador<br>
  #### &nbsp; &nbsp; 1.5 Incidencias<br>
  #### &nbsp; &nbsp; 1.6 Credenciales<br>
 ### 2. Instalación.<br>
 ### 3. Creación. <br>


### 1.1-Menu principal
En este menu se le ofrece a los usuarios 3 opciones:<br> 
<br>-Iniciar sesion:  Segun el tipo de usuario que seas aparecera un menu distinto(usuario, tecnico, administrador).<br>
<br>-Registrarse: Permite registrarnos en la aplicación, esta opción solo esta disponible para los clientes ya que los tecnicos son dados de alta por el administrador <br>
<br>-Cerrar el programa.<br>

![Main_Menu](https://cdn.discordapp.com/attachments/892785104798224445/930149599723794542/unknown.png "Main_Menu")
### 1.2-Usuario básico
Al iniciar sesión como usuario normal aparece un menu que nos permite registrar incidencias, consultar las incidencias que hay abiertas, 
consultar las incidencias que hay cerradas, mostrar el perfil del usuario, cambiar la clave de acceso y cerrar sesión. Además al crear el usuario se generará un código aleatorio
que será enviado a su correo para verificar la autenticidad de su cuenta. El token deberá ser introducido en el programa correctamente para que pueda iniciar 
sesión con su nueva cuenta. La última versión del programa ya cuenta con el envío de datos por Gmail.

![Usuario_basico_menu](https://cdn.discordapp.com/attachments/892785104798224445/930154576550723644/unknown.png "Usuario_basico_menu")
![asdd](https://media.discordapp.net/attachments/892785104798224445/938924774858567720/unknown.png "asdd")
![](https://media.discordapp.net/attachments/892785104798224445/938925205890416690/unknown.png)

-Al pulsar la primera opción nos pide que introduzcamos el motivo de nuestra incidencia y se registra la incidencia.<br>
-Al pulsar la segunda opción se muestra por pantalla la lista de incidencias abiertas que tiene el usuario.<br>
-Al pulsar la tercera opción se muestra por pantalla las incidencias que ya han sido resueltas y un comentario del tecnico que la ha resuelto.<br>
-Al pulsar la cuarta opción nos muestra nuestro perfil el cual consta de nuestro nombre de usuario y nombres y apellidos.<br>
-Al pulsar la quinta opción nos pide nuestra contraseña actual para poder cambiarla y la nueva que querramos usar.<br>
-Al pulsar la sexta opción se cierra la sesión.
### 1.3-Usuario técnico
Al iniciar sesión como usuario técnico se muestra un menu con el cual podemos consultar las incidencias que tiene asignado el tecnico, marcar una incidencia como cerrada es decir cerrar esa incidencia, consultar las incidencias que ha resuelto ese técnico, mostrar el perfil del técnico, cambiar la clave de acceso y cerrar sesión.<br><br>
![Menu_Técnico](https://cdn.discordapp.com/attachments/892785104798224445/930171073390051378/unknown.png "Menu_Técnico")
<br><br>-Al pulsar la primera opción  muestra las incidencias que este técnico tiene asignadas a su perfil.<br>
-Al pulsar la segunda opción  permite cerrar una incidencia primero  muestra las incidencias asignadas y le pide que elija la que quiere cerrar, despues pide introducir un comentario para que el tecnico explique lo que pasaba y se cierra esta incidencia.<br>
-Al pulsar la tercera opción nos muestra todas las incidencias resueltas por el técnico.<br>
-Al pulsar la cuarta opción muestra el perfil del técnico el cual consta de un nombre de usuario junto a su codigo de tecnico y el nombre y apellidos de este.<br>
-Al pulsar la quinta opción nos pide nuestra contraseña actual para poder cambiarla y la nueva que querramos usar.<br>
-Al pulsar la sexta opción se cierra la sesión.<br>
### 1.4-Usuario Administrador
Al iniciar sesión como administrador se nos despliega el menu de administrador y con este menu podemos consultar todas las incidencias, 
consultar todos los usuarios, consultar todos los técnicos, asignar incidencias a los técnicos, dar de alta a técnicos, dar de baja a técnicos y cerar sesión. Además
, cuando el administrador registre una nueva incidencia se notificará vía Telegram.<br><br>

![Menu_administrador](https://cdn.discordapp.com/attachments/892785104798224445/930176865740660826/unknown.png "Menu_administrador")
![](https://media.discordapp.net/attachments/892785104798224445/938926577679495228/unknown.png)
<br><br>-Al pulsar la primera opción nos muestra todas las incidencias que existen.<br>
-Al pulsar la segunda opción nos muestra todos los usuarios que esten registrados en nuestro programa.<br>
-Al pulsar la tercera opción nos muestra todos los tecnicos que esten dados de alta en nuestro programa.<br>
-Al pulsar la cuarta opción nos enseña las incidencias que no tienen ningun técnico asignado la elegimos introduciendo el numero que le corresponde y despues elegimos el tecnico al cual queremos asignar esta incidencia y se asignaria al tecnico que elijamos.<br>
-Al pulsar la quinta opción nos da opcion a dar de alta a un tecnico lo unic que tendremos que hacer es introducir sus datos y crear un código de técnico el cual debe de constar de 7 caracteres<br>
-Al pulsar la sexta tecla nos muestra los tecnicos que hay dados de alta y introduciendo el numero que ocupa el técnico procederiamos a borrarlo.<br>
-Al pulsar la septima opción cerramos sesión.<br>
### 1.5 Incidencias
-Al crear una incidencia se generará un número aleatorio (entre 1-100.000). Este código será único para cada incidencia, así podremos encontrarlo más rápido.<br>
  ![asd](https://media.discordapp.net/attachments/892785104798224445/938918379060858900/unknown.png "asd")

### 1.6-Credenciales
Credenciales usuario:<br>
Usuario 1: Nombre de usuario es agc@gmail.com y la contraseña 123456.<br><br>
Credenciales técnicos:<br>
Tecnico 1: Nombre de usuario jur@gmail.com y la contraseña 1234.<br>
Tecnico 2: Nombre de usuario adgc@gmail.com y la contraseña 12345.<br><br>
Credenciales administrador:<br>
Administrador: Nombre de usuario lcm@gmail.com y la contraseña 123.<br>
## 2-Instalación 
!!Importante habra que instalar JRE atraves de este link https://javadl.oracle.com/webapps/download/AutoDL?BundleId=245448_4d5417147a92418ea8b615e228bb6935<br>
Entramos al link de github https://github.com/Jorgeur710/PracticaObligatoria2.git lo clickamos y nos llevara a github, pinchamos en el boton verde que pone codigo y lo descargamos como zip.<br>
![Foto instalacion](https://cdn.discordapp.com/attachments/892785104798224445/930192153383149578/unknown.png "Foto instalacion")
<br> Una vez descargado abrimos el zip y buscamos en el buscador C:\ y pulsamos enter<br>
![C:](https://cdn.discordapp.com/attachments/892785104798224445/930192823876218992/unknown.png "C:")
<br>Aqui creamos una carpeta con el nombre que queramos y metemos dentro la carpeta que se encuentra dentro del archivo.zip que hemos descargado previamente, una vez ahi abrimos la carpeta "PracticaObligatoria2-master" despues abrimos "out", "production", "PracticaObligatoria2", y ahi clicamos en el archivo ejecutable Main.<br>
![Captura_C](https://cdn.discordapp.com/attachments/892785104798224445/930194756544393256/unknown.png "Captura_C")

## 3- Creación
Programa desarrollado por Alberto García Carreras y Jorge Ureña Rubia
