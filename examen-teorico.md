# EXAMEN JAVIER LÓPEZ RODRIGO 
# Preguntas obligatorias
## 1. ¿Quién es Philip Meyer?
### Philip Meyer es el inventor del Precision Journalism, publicado en 1973. Actualmente es catedrático en la Universidad de Carolina del Norte. 

## 2. ¿Quién fue Florence Nightingale?
### Florence Nightingale fue una enfermera que aportó muchas técnicas de estadística al estudio de las patologías a finales del siglo XIX.


# Bloque B

## 1. Cuál fue el comienzo del CAR (Computer Assisted Reporting)?
### El Computer Assisted Reporting o periodismo asistido por ordenadores lleva funcionando en EE.UU. desde los 1950. Fue empleado por la CBS para analizar los datos de las elecciones presidenciasles, de 1952, para averiguar cual iba a ser la intención de voto de los estadounidenses, dando una previsión ficticia.

## 2. ¿Qué es nano?
### Nano es un editor de texto minimalista de la línea de comandos, que además tiene otras características que lo hacen útil como modificar archivos de configuración en la terminal, crear lanzadores, etc.

## 3. ¿Cuál es la estructura de las sentencias/instrucciones en la línea de comandos?
### La estructura de las sentencias o instrucciones en una línea de comandos se componen de las siguientes partes:
### Principalmente encontramos la palabra reservada o instrucción, es decir, la palabra que indica que comando se va a ejecutar.
## Ejemplo: nano, ls
### Después va a la función de Opción. En algunos comandos se introducen unos caracteres que suelen ir seguidos de - para indicar alguna opción en concreto de la instrucción.
## Ejemplo: -l
### Finalmente tenemos que introducir la ruta. En la mayoría de comandos hay que indicar el archivo sobre el que se va a ejecutar la instrucción.

## 4. ¿Cuál es la versión de Shell qué utilizas?
### Se puede comprobar qué shell tienes con el comando echo $SHELL. Por tanto, al ponerlo me sale: /bin/zsh, por lo tanto introduzco otro comando como es el siguiente para que me de la versión que tengo en mi ordenador: [$SHELL --version]. Y el resultado es este: zsh 5.8.1 (x86_64-apple-darwin21.0)

## 5. ¿Cómo verías las variable de entorno de tu shell "PATH"? Escribe su valor también.
### Las variables se pueden ver con el comando [env]. Como salen muchas cosas en la pantalla y no se pueden leer todas será mejor "paginar" el resultado con [less].
### Tanto [less] como [more] son paginadores de texto, visores de texto.
### Si con [>] enviamos la salida estándar a un archivo, en este caso se usa el operador [|] que envía la salida a un comando:[env|less] .
### El operador es la barra vertical | que se escribe con [Alt gr +1]. También se puede ver el valor de una variable con el comando [echo] seguido de la variable, es decir, precedida del símbolo del dólar que indica que se trata de una variable:[echo $PATH].

## 6. Cuál es el primer comando que deberías usar en la terminal. Explica tu respuesta.
### El primer comando que se debe utilizar en una termila es pwd, ya que te dice donde estás (print working directory). Este comando es útil ya que es necesario saber donde estás para poder realizar diferentes acciones en la terminal, ubicarte en el directorio correcto y trabajar desde ahí por ejemplo.

## 7. ¿Qué se puede hacer para ver el contenido de un archivo de texto?
### Para visualizar el contenido de un archivo de texto podemos usar el comando TYPE. Podremos ver el contenido de un archivo pero no lo podremos editar. Y se puede usar con rutas relativas o absolutas.


# Pregunta de desarrollo
## 3. Qué formatos de datos hay:

### En el periodismo de datos existen diferentes formatos: 
### 1. XML: Es un formato muy complejo para el nivel en que nos encontramos. Significa eXtensible Markup Language. Se trata de un formato complejo de leer, por eso no lo hemos utilizado, ya que claro está que es más complicado trabajar con este tipo de archivos.

### 2. JSON: Significa o JavaScript Object Notation. Permite más complejidad de CSV, pero tambien es más difícil de leer. Son los ficheros que mejor funcionan con aplicaciones web y Utilizan la sintaxis de JS, la cual define un conjunto de reglas que deben seguirse para escribir código correctamente, y darle así instrucciones al programa en el que estemos trabajando, ejecutando la tarea especificada de dicho código.

### 3. *SV: Se trata del comando más usado y más facil de utilizar, suele estar presente en la mayoría de las bases de datos abiertas, con terminación [csv]. Incluso aunque no se empleen comas para separar los valores, son mñas sencillos, pero los menos estandarizados. Los valores separados por comas se pueden ver. 
### Los valores separados por comas se visualizan como una tabla simple con filas y columnas.
### La mayoría de los recursos disponibles en los catálogos de Datos Abiertos se encuentran en formato CSV. Un ejemplo de ello es el portal de datos europeo dispone de más de 120 mil conjuntos de datos en formato CSV, siendo el formato que más abunda en este catálogo de Datos Abiertos, o también a nivel nacional, [el Gobierno de España](datos.gob.es) cuenta con casi 14 mil datasets en formato CSV, siendo igualmente el formato mayoritario.
