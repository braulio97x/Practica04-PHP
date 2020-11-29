# Practica04-PHP
PHP con Base de datos
1. El desarrollo de cada uno de los requerimientos antesdescritos.

Revisar y analizar el código de php del punto (f).

1. **¿Qué realiza la sentencia include en PHP?**

La sentencia include incluye y evalúa el archivo especificado.

1. **¿Qué es la variable $\_POST?**

POST nos permite recuperar datos enviados desde formularios con el método POST.

1. **¿Qué hace la función isset()?**

Dicha función comprueba si una variable está definida o no en el script de PHP que se está ejecutando.

1. **¿Qué hace la función trim()?**

Nos permite eliminar espacios en blanco u otros caracteres al inicio y final de una cadena de texto.

1. **¿Qué hace la función strtoupper()?**

Convierte a mayúsculas los caracteres de una cadena string.

1. **¿La función MD5 es de PHP?**

Si es de PHP md5 y sirve para calcula el &#39;hash&#39; md5 de un string.

El valor o cadena devueltos es el hash representado como un número hexadecimal de 32 caracteres.

1. **¿Por qué utilizamos la función MD5?**

Para convertir la contraseña en una cadena de 32 caracteres en hexadecimal, en otras palabras para sirve para cifrar la variable contraseña.

1. **¿Por qué agregamos el código 0?**

Por qué pertenece al campo `usu_codigo` int(11) NOT NULL AUTO\_INCREMENT de la tabla usuario

1. **¿Cuál es el error 1062 en mysql?**

1062 - Entrada duplicada, se produce cuando la columna de clave principal es única y no aceptará la entrada duplicada. Por lo tanto, cuando intente insertar una nueva fila que ya está presente en su tabla, se producirá este error.

1. **¿Por qué los dos últimos valores de la sentencia SQL son null?**

Por qué no es un tipo de datos, ya que hacen referencia al:

![](RackMultipart20201129-4-b8ydk4_html_c6e2e0a6dcd72aa5.png)

1. **La función query(), ¿para que tipo de consultas SQL se utiliza?**

Ejecuta una sentencia SQL, devolviendo un conjunto de resultados como un objeto PDOStatement.

query() devuelve un objeto PDOStatement, o FALSE en caso de error.

query() ejecuta una sentencia SQL en una única llamada a función, devolviendo el conjunto de resultados (si los hay) que devuelve la sentencia como un objeto PDOStatement.

1. **¿Qué realiza la función mysqli\_error()?**

Devuelve una cadena que describe el último error, caso contrario devuelve una cadena vacía si no ha ocurrido error alguno.

1. **¿Qué realiza la función close()?**

Cierra una conexión previamente abierta a una base de datos

**14. ¿Se puede tener etiquetas html y código php en el mismo archivo?. En caso que la respuesta sea afirmativa, el archivo ¿deberá tener extensión html o php? ¿Porqué?. En caso que la respuesta sea negativa. ¿Porqué no?**

No se puede tener etiquetas html y código php en el mismo archivo por que los archivos html son leídos directamente por el navegador y el navegador no es capaz de reconocer el código php, es decir, un archivo php necesita que un intérprete php que lo procese, ya que los archivos php tienen que estar situados en un servidor y hay que solicitarle al servidor que interprete el archivo (escribiendo la url en el navegador) y devuelva el código html que se genera.

**15. ¿La etiqueta meta en el head es necesario? ¿Qué pasa si no se pone esta etiqueta?**

Las etiquetas meta o meta tags encabezan un documento HTML y suministran información codificada a navegadores y motores de búsqueda sobre una página web. Los metadatos son invisibles para el usuario y se encargan de añadir información para facilitar el análisis de los archivos HTML y la gestión del contenido de una página web.

**16. Ingresar datos con tíldes o caracteres latinos. ¿Cómo se guarda en la base de datos?**

Los datos se alteran, acabando en Ã¡Ã³Ã± y cosas parecidas., por ello todos los ficheros PHP y HTML de nuestro sitio web deben estar guardados en formato UTF-8

**h. Revisar y analizar el código de php del punto (d).**

**1. ¿Qué realiza la función session\_start()?**

session\_start() crea una sesión o reanuda la actual basada en un identificador de sesión pasado mediante una petición GET o POST, o pasado mediante una cookie.

Cuando session\_start() es llamada o cuando se autoinicia una sesión, PHP llamará a los gestores de almacenamiento de sesiones open y read.

**2. ¿Qué se almacena en la variable $result?**

Se guardó el resultado de la consulta sql, en este caso el usuario que coincida con su nombre y contraseña.

**3. ¿Qué es la variable $\_SESSION de php?**

Es un array asociativo que contiene variables de sesión disponibles para el script actual. Esta es una &#39;superglobal&#39; o una variable automatic global. Significa simplemente que es una variable que está disponible en cualquier parte del script.

**4. ¿Qué realiza la función header?**

header — Enviar encabezado sin formato HTTP

Recuerde que header() debe ser llamado antes de mostrar nada por pantalla, etiquetas HTML, líneas en blanco desde un fichero o desde PHP.

**5. ¿Qué realiza el parámetro Location de la función header?**

El segundo caso especial es el encabezado &quot;Location:&quot; No solamente envía el encabezado al navegador, sino que también devuelve el código de status (302) REDIRECT al navegador a no ser que el código de status 201 o 3xx ya haya sido enviado.

**g. Revisar y analizar el código de php del punto (c).**

**1. ¿Qué realiza la función fecth\_assoc()?**

mysqli\_result::fetch\_assoc -- mysqli\_fetch\_assoc — Obtener una fila de resultado como un array asociativo.

Devuelve un array asociativo de strings que representa a la fila obtenida del conjunto de resultados, donde cada clave del array representa el nombre de una de las columnas de éste; o NULL si no hubieran más filas en dicho conjunto de resultados.

**2. ¿Qué se almacena en la variable $row?**

El nombre de las columnas de la tabla.

**3. ¿Cuál es el método http que se usa para enviar parámetros a través de la URL?**

Con el método GET, los datos que se envían al servidor se escriben en la misma dirección URL. En la ventana del navegador, lo encontrarás así:

www.ejemplo.com/registrarse.php?nombre=pedro&amp;amp;apellido=perez&amp;amp;edad=55&amp;amp;genero=hombre

Los parámetros URL se pueden guardar junto a la dirección URL como marcador. De esta manera, puedes introducir una búsqueda y más tarde consultarla de nuevo fácilmente. También se puede volver a acceder a la página a través del historial del navegador.

**4. ¿Qué hace la super variable $\_GET?**

$\_GET -- $HTTP\_GET\_VARS [obsoleta] — Variables HTTP GET

Un array asociativo de variables pasado al script actual vía parámetros URL (también conocida como cadena de consulta). Tenga en cuenta que el array no solo se rellena para las solicitudes GET, sino para todas las solicitudes con una cadena de consulta.

Esta es una &#39;superglobal&#39; o una variable automatic global. Significa simplemente que es una variable que está disponible en cualquier parte del script.

**. Revisar y analizar el código de php del punto (g).**

1. **¿Qué hace la función date\_default\_timezone\_set ?**

date\_default\_timezone\_set — Establece la zona horaria predeterminada usada por todas las funciones de fecha/hora en un script.

1. **¿Qué hace la función date ?**

date — Dar formato a la fecha/hora local

Devuelve una cadena formateada según el formato dado usando el parámetro de tipo integer timestamp dado o el momento actual si no se da una marca de tiempo. En otras palabras, timestamp es opcional y por defecto es el valor de time().

1. **¿Qué hace la función time ?**

time — Devuelve la fecha Unix actual

Devuelve el momento actual medido como el número de segundos desde la Época Unix (1 de Enero de 1970 00:00:00 GMT).

1. **¿Qué hace la super variable $\_GET?**
Un array asociativo de variables pasado al script actual vía parámetros URL (también conocida como cadena de consulta). Tenga en cuenta que el array no solo se rellena para las solicitudes GET, sino para todas las solicitudes con una cadena de consulta.
