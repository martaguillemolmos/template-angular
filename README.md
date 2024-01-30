# Plantilla, Angular 17.

Antes de iniciar el proyecto de Angular, deberemos comprobar que nuestro sistema tengamos Node instalado.

     node --version

>[!IMPORTANT]
>Comprueba que la version de Node instalada, sea compatible con Angular 17.
  
Seguidamente, instalaremos Angular CLI de forma global.

    npm install -g @angular/cli

Si ya tienes instalado, comprabaremos la versión de este framework, a través del siguiente comando desde la terminal.
    
    ng version

<div align="center">
      <img src="./img_readme/Comprobar vesión Angular CLI.png" alt="Inicializar el proyecto" style="max-width: 100%" /> 
   </div>    
   <div align="center">
    <em>Comprobar vesión Angular CLI</em>
    </div>
<div>
<br>

Antes de continuar, debes saber que los términos Angular CLI y Angular, son diferentes.

- <em>Angular CLI:</em> Es una herramienta para inicializar, desarrollar, automatizar y mantener aplicaciones Angular.
- <em>Angular:</em> Es una plataforma de desarrollo para crear aplicaciones web móviles y de escritorio utilizando Typescript/JavaScript y otros lenguajes.

<em>Una vez que creas tu aplicación con el comando ng create seguido en nombre del proyecto, Angular CLI creará una aplicación con Angular.</em>

## Inicializar el proyecto con Angular 17

Abrimos Visual Studio Code, seleccionamos la carpeta e inicializaremos el proyecto ejecutando en la terminal el siguiente comando:

    ng new angular-desde-cero

Tras ejecutar el comando, deberemos de seleccionar el estilo.En este caso, seleccionaremos CSS.

<div align="center">
      <img src="./img_readme/1- Inicializar proyecto.png" alt="Inicializar el proyecto" style="max-width: 100%" /> 
   </div>    
   <div align="center">
    <em>Seleccionar el estilo.</em>
    </div>
<div>
<br>

A continuación, deberemos seleccionar si queremos que de forma nativa, queremos que nuestro proyecto contenga serve-arrendering. En nuestro caso, seleccionaremos NO.
Y de forma automática, se generarán todos los archivos, siguiendo la siguiente estructura.

<div align="center">
      <img src="./img_readme/3- Estructura del proyecto.png" alt="Estructura del proyecto" style="max-width: 100%" /> 
   </div>    
   <div align="center">
    <em>Estructura de carpetas</em>
    </div>
<div>
<br>

Por último, para poder visualizar en línea el proyecto que hemos creado,deberemos de ejecutar el siguiente comando a través de la terminal.

    ng serve
    

<div align="center">
      <img src="./img_readme/4- Angular en linea.png" alt="Angular en línea" style="max-width: 100%" /> 
   </div>    
   <div align="center">
    <em>Así se visualiza el proyecto de Angular17 antes de realizar cualquier modificación en él.</em>
    </div>
<div>

