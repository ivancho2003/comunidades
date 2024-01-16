# comunidades
## Instrucciones
Cada uno debe generar un componente dentro del react , para ello deben descargar el documento y modificarlo en sus pc , ademas de generar un commit en el proyecto
## Como sincronizar sus computadoras con su cuenta 
1.- Descargar gitbash 

2.- Configurar gitbash

3.- En git bash usar el comando git config --global user.name "Su nombre de usuario en github" y presionar enter 

4.- Otra vez en gitvash ingresar el comando git config --global user.email Su correo de github

## Sincronizar su computador mediante SSH

1.- Abra Git Bash.

2.- Pegar el texto siguiente, reemplazando el correo electrónico por tu dirección de correo electrónico de GitHub.
ssh-keygen -t ed25519 -C "your_email@example.com"

3.-Cuando se te pida: "Introduce un archivo en el que se pueda guardar la clave", teclea Enter para aceptar la ubicación de archivo predeterminada

4.-En la esquina superior derecha o izquierda de cualquier página de github , haga clic en su foto del perfil y, luego, en Settings (Configuración).

5.En la sección "Acceso" de la barra lateral, haz clic en  Claves SSH y GPG.

6.Haga clic en Nueva clave SSH o en Agregar clave SSH.

7.En el campo "Title" (Título), agrega una etiqueta descriptiva para la clave nueva. Por ejemplo, si estás utilizando un portátil personal, puedes llamar a esta clave "Portátil personal".

8.Selecciona el tipo de clave, ya sea de autenticación o de firma. Para más información sobre la firma de confirmación, consulta "Acerca de la verificación de firma de confirmación".

9.En el campo "Clave", pega tu clave pública.

## Como realizar un commit

0.-Abrir el archivo en visual studio code , para esto hacer uso del comando git clone https://github.com/ivancho2003/comunidades.git

1.-Crear un componente dentro de la carpeta components 

2.-Abrir la terminal con control + ñ

3.-Escribir en la terminal git add . y presionar enter

4.-Escribir en la terminal git commit -m "Creacion componente nombre"//Nombre es su nombre

5.-git branch -M main

6.-git remote add origin https://github.com/ivancho2003/comunidades.git

7.-git push -u origin main

## Consejos
En caso de no poder realizar los anteriores pasos , solo moverse por el documento y agregarlo de manera directa
