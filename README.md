# Introduccion-a-linux
Primeros pasos en Linux Ubuntu
 Linuz es unsistema operativo de uso libre, quiere decir qu eno ocupa licensia para ser instalado, así como hya versiones del sistema operativo de Windows tambien las hay en Linux, una de ellas es Ubuntu Debian.
 
Hay muchas mas versiones de sistemas operativos basados en linux y pueden encontrarse algunas mucho mas especificas para actividades en particular, si se desea conecer más al respecto se recomienda ver [Ubuntu Flavors](https://ubuntu.com/desktop/flavours).
 
Legalmente usa licencia tipo creative commons -> licencia de comercialización

A diferencia de Windows y MacOS Linux es para usuarios de nivel medio-avanzado, por lo que se recomienda leer la información proporcionada en la terminal al usar cualquier comando.

Ubuntu Debian presenta una interfaz grfica con la que el usuario puede sentrse mas familiar, por su semejanza con widows, se trabaja en carpetasy tienes iconos de las aplicaciones, se cuenta con una tienda de aplicaciones y se tiene acceso a aplicaciones semejantes a las herramientas clasicas de Office 

## Comandos de terminal
Es muy frecuente usar comandos en la ventana terminal de sistema, con ellos podemos ejecutar aplicaciones, programaas, acceder a carpetas, modificarlas, ver estatus del sistema, información de sistema, respuestas a las aplicaciones y programas etc.

### Descripción de la ventana terminal

![](https://github.com/RamsesOrtiz36/Introduccion-a-linux/blob/main/ventana%20terminal%20de%20comandos%20en%20ubuntu.png)

* Se accede con la combinación de teclas **Alt+Ctrl+t** o desde las aplicaciones (los 9 puntos abajo Iquierda de la pantalla)
* Recomendamos anclar la ventana de comandos a la barra lateral de tareas, 
* Se tiene el Promt Apuntador, **nombrede usuario@nombre de maquina** en color verde, nos indica que esta listo para recibir comandos del usuario
* Despues de los dos puntos ":" aparece la **vergulilla "~"** simbolo representante de la ubicación de directorio home.
* Si usamos el comando **ls** nos mostrara todos los archivos que se encuentran en esa ubicación
* las ubicaciones son los nombres de las carpetas separadas por "/" para indicar una subcarpeta, la ruta o path es la cadena de nombres de todas las carpetas que hay que abrir para llegar al archivo o programa que nos interesa.

![Comando ls](https://github.com/RamsesOrtiz36/Introduccion-a-linux/blob/main/comando%20ls.png)

Otros comandos utiles son:

    clear
    history
    cd
    
Estos coamndos respectivamente:
+ Limpian la ventana de comandos    
+ Muestra un historial de comandos usados recientemente
+ Cambia de directorio 

### Estructura de comandos
[Permiso] [Programa o comando] [Opciones] [parametro]

Para el comando ls [flags opcion] [directorio]
Las opciones se indican con el guion"-" separado con un espacio

El permiso de usuario se puede cambiar a permiso de root y modificar archivos del sistema para ello usamos el comando "sudo" = super user do.

### Otros comandos

Muestra valores de variables en terminal

    echo

Ubica archivo entregando la ruta

    whereis

Cambia de directorio

    cd [ubicación]

Entrega la ruta actual del prompt

    pwd 

Visualiza archivo sin modificarlo

    cat[Nombre arhivo.extension]

abre archivo o lo crea para editarlo

    touch

crea carpeta    

    mkdir

bora o renombra carpeta    

    rmdir
