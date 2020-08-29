# Ejercitación Node básico

### Leyendo archivos

1. Crear tres archivos de texto con cualquier contenido. 

2. Hacer una funcion que muestre en consola el contenido de los archivos. Debe usar fs.readFile, no fs.readFileSync. 

3. Hacer una funcion que uno de los archivos y cree un nuevo archivo con todo el texto del anterior en mayúsculas. 

4. Hacer una función que lea cada uno de los archivos y finalmente cree un cuarto archivo con el contenido de los tres restantes. 


### Server de gatitos

1. Utilizando el módulo http, crear un server en el puerto 3030 que retorne en la ruta base / el string "Gatitos!". 

2. Si el usuario ingresa a la ruta /mostrarGatito, se debe devolver un HTML con un h1 que diga "Gatito!" y la imagen del gatito de tu preferencia. 

3. Si el usuario ingresa a la ruta /fotosGatitos, se debe devolver [este json](https://gist.github.com/seanmtracey/567847581e86a4f4365b#file-cats-json)

4. Si el usuario ingresa a cualquier otra ruta, devolver un 404 incluyendo los headers correspondientes. 


### package.json

El comando `echo` en la consola sirve para devolver cualquier cosa que escribamos. Probá escribiendo "echo Hola" en tu terminal o consola. 

1. Corré el comando `npm init` en tu proyecto. 

2. Crear un script en package.json que reciba el comando "saludar". Al correr `npm run saludar` en la consola, debemos ver "Hola, este es mi primer script!".


### calcular Fecha

Usando el objeto Date podemos saber la fecha actual. 

`const fechaActual = new Date();`

O podemos saber una fecha en particular agregando números como argumentos:

`const navidad = new Date(2020,11,25);`

1. Crear una función en Node que calcule la fecha actual y la muestre en consola.

2. Crear una función que muestre en consola cuánto falta para tu cumpleaños (en milisegundos, que es lo que devuelve Date)

3. Instalar el paquete de npm `pretty-ms`. Investigarlo y utilizarlo para mostrar en consola cuántos días faltan para tu cumpleaños. 
