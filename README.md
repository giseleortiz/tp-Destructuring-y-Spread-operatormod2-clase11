
Práctica Integradora

Objetivo
En esta clase vamos a trabajar en grupo y experimentamos la diversidad de aplicaciones
que se pueden realizar gracias al entorno de desarrollo que nos ofrece Node.js. Para ello
usaremos los módulos nativos de Node.js y crearemos nuestros propios módulos. También
vamos a utilizar diversos recursos de programación que hemos venido utilizando en el
avance de nuestras clases.

Cuando tengas alguna duda que te impida avanzar, puedes preguntarle a tus compañeros y
profesores.

¡ Éxitos !

1

Micro desafío 1:

Instrucciones

DH-Pelis
El Tech Leader presenta al equipo un nuevo proyecto de compra y venta de
películas. Quiere que mostremos que tenemos claro cómo hacer para exportar e
importar nuestros propios módulos. Para ello, seguiremos los siguientes pasos:

a. Crear una carpeta llamada proyecto.
b. Dentro de ella crear un archivo llamado peliculas.js. Este archivo será un
módulo que contiene una lista con algunas de nuestras películas favoritas.
Para eso nos recomiendan crear un array de objetos literales. No olvides
que este archivo es un módulo propio y por tal motivo una vez que se crea...
¿cuál debería ser nuestra última línea de código?
Por cada película se necesita conocer esta información:
i. Identificador único de la película (id)
ii. Calificación por parte de los usuarios (rating)
iii. Premios (awards).
iv. Duración de la película (length).
v. Precio (price).
vi. Género de la película (genre):
1. Acción
2. Animación
3. Aventuras
4. Comedia
5. Suspenso.

c. Una vez creado el módulo anterior, crear un nuevo archivo (app.js). Piensa
cómo hacer para lograr importar nuestro módulo (peliculas.js). Luego,
utilizando lo que sabemos sobre ciclos o bucles, muestra al usuario un listado
con el detalle de cada una de nuestras películas favoritas.

2

Micro desafío 2:

El Tech Leader está muy agradecido por todo el esfuerzo realizado en el desafío anterior.
Ahora quiere saber si tenemos claro el uso de los módulos nativos de Node.JS. Por eso,
nos encomienda la siguiente tarea:
Instrucciones
1. En la carpeta ya creada, crea un nuevo archivo (mensaje.txt).
2. En el archivo creado, escribe el mensaje que quieras. Por ejemplo: “Node.js® es un
entorno de ejecución para JavaScript construido con V8, motor de JavaScript
de Chrome.”
3. Dentro del archivo (app.js), crea una variable a la que se le asigne la ruta del archivo
(mensaje.txt) y luego llama al módulo nativo de Node.js que te permita leer el
contenido del archivo (mensaje.txt).
4. Una vez leído, muestra al usuario por la consola el contenido del mismo.
