 Para el funcionamiento correcto de los comandos se debe configurar las variables de entorno y tener instalado el programa correspondiente.

===========================================================================
PARA EL EJECUTABLE "gitb" 
===========================================================================
FUNCION: en consola o cmd escribir ("gitb" + Enter) y poder abrir git bash en la ruta actual.

EJEMPLO: 

      PASO 1 :
      *Ubicamos en la ruta de nuestro proyecto y escribirmos: 
      C:\USERS\USUARIO\DESKTOP\PROYECTO> GITB
                 
      PASO 2: 
      Pulsamos ENTER y el resultado final sera git bash abierto en la ruta : C:\USERS\USUARIO\DESKTOP\PROYECTO
      
      PASO3: configurar la ruta C:\MyCommands en variables de entorno de windows.

      
===========================================================================
PARA EL EJECUTABLE "npm" 
===========================================================================
FUNCION: reemplazar npm por pnpm, es decir cuando por error ejecutes npm al mommento de instalar dependencias en un proyecto de react, angular o vue, este .bat reemplazara npm por pnpm, para una instalacion de dependencias mas segura.

EJEMPLO:
      PASO 1: 
      *Ejecutamos npm -v en la consola de comandos 
      C:\USERS\USUARIO\DESKTOP\PROYECTO> npm -v
            11.1.1
      PASO 2:
      *Ejecutamos pnpm -v en la consola de comandos 
      C:\USERS\USUARIO\DESKTOP\PROYECTO> pnpm -v
            11.11.1
      
      Observacion: Podemos ver que npm y pnpm son comandos distintos, por esa razon nos devuelven distintas versiones al ejecutar (pnpm -v y npm -v)

      PASO 3: cargamos el archivo npm.bat en la carpeta donde almacenamos los scripts. (en mi caso C:\MyCommands\)

      PASO 4: configurar la ruta C:\MyCommands en variables de entorno de windows.

      PASO 5: Volvemos a ejecutar npm -v y pnpm -v en la consola de comandos y deveria devolver la version de pnpm

      C:\USERS\USUARIO\DESKTOP\PROYECTO> npm -v
            11.11.1
            
      C:\USERS\USUARIO\DESKTOP\PROYECTO> pnpm -v
            11.11.1