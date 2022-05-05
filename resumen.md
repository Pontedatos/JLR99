# Resumen asignatura

## En este documento, voy a realizar un pequeño resumen sobre la materia aprendida en la asignatura.

## 1. Instalación de un programa de emulación de la terminal

### Durante el curso, teniendo como sistema operativo MacOS, hemos instalado dos terminales diferentes.

### Lo primero que hicimos para poder comenzar esta asignatura fue instalar, en el caso de las personas que contábamos con Mac, xcode a través de la terminal. Mediante esto podíamos emular BASH que se usa para ejecutar Git desde la línea de comandos.

### Para visualizar todos los pasos que hemos hecho en dicha terminal, se ha abierto el documento del historial con el siguiente comando “cat .bash_history”.


## 2. Configuración del programa

### Lo primero que hicimos fue meternos en nuestra carpeta local de Periodismo de datos con el comand cd y la correspondiente dirección de nuestro ordenador donde se encuentran los datos. A continuación, miramos el contenido de la carpeta con el comando ls y creamos una nueva carpeta con mkdir llamada. Después nos metimos en la carpeta, de nuevo con el comando cd.

### Primero se estableció alias micasa y se igualó a la dirección de carpeta que queríamos (alias micasa="cd Documents/Universidad/5º/2º\ cuatri/Periodismo\ de\ Datos/"). A continuación con el comando echo establecemos que la terminal sepa cuál es la home, entonces hicimos “echo $home” y luego lo hacemos con nuestra carpeta de periodismo de datos: “echo "alias micasa='cd Documents/Universidad/5º/2º\ cuatri/Periodismo\ de\ Datos/'”. Después, abrimos el el archivo nano (nano $HOME/.bashrc) y escribimos lo siguiente: #Aqui creo un alias para ir a mi directorio de trabajo en clase alias micasa="cd Documents/Universidad/5º/2º\ cuatri/Periodismo\ de\ Datos/" Esto es para que la terminal guardase la dirección.


## Configurar GitHub

### El paso siguiente fue clonar nuestro repositorio personal con el comando git clone https://github.com/JLR99/practica1_periodismodatos.git practica-1. Una vez, trasladado nuestro repositorio a nuestro archivo local, abrimos el archivo README.md con el comando cat. También editamos el texto con nano. Luego establecimos nuestra carpeta de periodismo de datos como nuestra home predeterminada. Empleamos “git init” para copiar todas las propiedades de la carpeta de github a nuestro repositorio del ordenador. Posteriormente, configuramos el nombre de usuario y el correo electrónico git config --global user.name git config --global user.email. Y después, configuramos para que nuestro editor de texto sea nano en nuestra terminal Git Bash. Lo realizamos con el comando git config --global core.editor nano.

## 3. Configuración de un programa de edición de texto

### Para poder configurar el programa de edición de texto, en nuestro caso, nano con el archivo de configuración. Para ello, abrimos el archivo nano de configuración: nano $HOME/.nanorc (en Git Bash) y nano /c/Users/Javier/ .nanorc y ponemos lo siguiente: Git Bash: ##Spread overlong lines over multiple screen lines. set softwrap ##Display line numbers to the left of the text. set linenumbers

### Podemos editar el comportamiento de nuestro editor de texto nano a través de su archivo de configuración. En nuestro caso, vamos a hacer que se ajuste el texto a la resolución de la pantalla y que aparezca el número de las líneas para poder visualizar y localizar mejor el contenido del archivo. Para ello, lo editamos de la siguiente forma: nano $HOME/.nanorc y ponemos lo siguiente: #Ajustar el texto a pantalla set softwrap #Numerar las líneas set linenumbers

## 4. Configuración y funcionamiento de un gestor de paquetes/programas del emulador de la terminal.

### Primero antes de adentrárnos en este punto, voy a definir qué es un gestor de paquetes. Según OpenWeibnars es el conjunto de herramientas que facilitan el proceso de instalación y muestran la información de los paquetes y dependencia. En el caso de GitBash y Cygwin, el gestor de paquetes es apt-cyg. Un APT (Advanced Package Tool) es un conjunto de herramientas que permite manejar los paquetes de los sistemas. En nuestro caso, hemos instalado apt-cyg install tree (esta es para que la información salga mostrada en forma de árbol) y apt-cyg install git. apt-cyg install ruby y gem instal lolcat, este último en cygwin.

## 5. Versión del lenguaje de SHELL utilizado.

### Según los apuntes de Periodismo de Datos, Shell es el lenguaje que emplea la terminal. Para comprobar cuál es en GitBash ejecutamos el comando echo $0 y nos encontramos que es el siguiente: /usr/bin/bash. Para saber qué versión de Bash está manejando lo hacemos con el comando “bash -help” y nos da la información: GNU bash, version 4.4.23(2)-release-(x86_64-pc-msys). En Cygwin realizamos los mismos pasos: Ejecutamos el comando echo $0 y nos dice que el lenguaje es: -bash Después ponemos “bash -help” y nos da la versión de Bash de Cygwin GNU bash, version 4.4.12(3)-release-(x86_64-unknown-cygwin)

## 6. Valor de la variable de entorno PATH

### Para poder consultar la variable de entorno PATH lo ejecutamos con el comando “echo $PATH” que nos da la información de donde está la ruta de la terminal instalada en nuestro ordenador.


## 7. Comandos utilizados 


### pwd: nos indica en qué carpeta o directorio nos encontramos.

### cd: nos permite movernos a unn directorio diferente al que estamos.

### ls: con este comando nos muestra o lista el interior de una carpeta de un directorio.

### nano: es el comando con el que se nos abre el editor de texto nano y podemos editar archivos markdown

### mkdir: con él podemos crear carpetas.

### cat: dicho comando sirve para concantenar o unir archivos. También tiene una doble función que es visualizar los archivos markdown.

### mv: su función es mover un archivo de un origen a otro destino diferente.

### echo: con este comando, podemos decirle a la terminal que nos diga una serie de palabras y nos lo devolverá escrito poniendo echo “hola mundo”, la terminal te responde lo que has escrito entre comillas.

### cp: nos permite copiar archivos de una carpeta origen a otra destinataria.

### git init: traslada las características de nuestro repositorio de Github a nuestra carpeta local del ordenador.

### whoami: la terminal te devuelve quién eres.

### Git clone: se clona el repositorio en tu carpeta local del ordenador.
