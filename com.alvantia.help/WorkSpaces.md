Para la creacion de un nuevo WorkSpace, vamos a necesitar lo siguiente: 

- #IDE 
- #Git 
- #JDK
- #Maven 
- #Node 
- #NPM 
- Plugins:
	- Sonarlint
	- MyBatipse
	- Lombok [Descargar](https://projectlombok.org/download)

Lo primero que tenemos que entender es que es un WorkSpace, para ello vamos a diferenciarlo de la carpeta donde estará alojado nuestro proyecto clonado de git. 

Un WorkSpace es un entorno de trabajo donde nosotros importaremos los proyectos que queramos de manera que podamos tener entornos en los que solo tengamos varios proyectos, para trabjar de forma mas ligera, o donde tengamos toda la aplicacion con la totalidad de los proyectos importados para poder movernos por ellos. Es importante saber que estos entornos, no copian los archivos a las carpetas generadas, si no que sera una carpeta en la que se guarde la configuracion del entorno, asi como ciertas peculiaridades como las siguientes: 

- Operar con distintas versiones de JDK
- Operar con distintos archivos settings

Lo primero de todo, sera abrir nuestro IDE que más nos guste, yo usaré #SpringToolsSuite para el ejemplo.
	![[sts.wks.init.png]]

En esta ventana, le daremos a "New", y especificaremos la ruta donde alojaremos nuestro WorkSpace y cuando tengamos seleccionada la carpeta, le damos al "Play". Tardará una poco en la creación del espacio.

--------

Os dejo aquí la forma de ponerlo en modo oscuro, por si os molesta el modo claro, aunque va a gusto de cada uno: 
	Una vez estemos dentro, iremos a la barra de los menús de arriba: 
	Window--->Preferences--->(Buscar)Appearance--->Click en la opción--->Theme 
	y en este desplegable cambiamos a Dark, hay opciones de poder descargar plugins con diferentes temas tanto para apariencia como para fonts, a gusto del consumidor

------
Importante, que siempre que creemos un nuevo WorkSpace, tengamos en cuenta que debemos de configurar ciertas cosa como son la version de JDK que vamos a usar y el archivo settings, que tengamos propio de la empresa o cliente, para que cojas las configuraciones correctas para poder buildear nuestros proyectos sin que nos de fallo.
![[sts.wks.init1.png]]
![[sts.wks.init2.png]]
![[sts.wks.init3.png]]
![[sts.wks.init4.png]]

Una vez esten estas cosas, ya estamos listos para importar nuestros proyectos de git.
