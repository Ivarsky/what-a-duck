# Wallapop Clon

Proyecto de clon de wallapop realizado por el equipo Mighty Ducks.

Creado con express generator y create react app

El proyecto esta siendo servido en la url:

http://ec2-3-81-159-152.compute-1.amazonaws.com/

Pero no hemos podido hacer que funcione completamente en el servidor por razones que se explicarán durante la presentación del proyecto, por lo tanto abajo se adjuntan instrucciones para hacerlo correr en local.

## Instalacion de dependencias

En la carpeta backend ejecutar comando

```
npm i
```

En la carpeta de frontend en terminal separada ejecutar el mismo comando

```
npm i
```

## Variables de entorno

En las carpetas backend (.env-example) y frontend (.env.local.example) se encuentran los ficheros de ejemplo para configurar las variables de entorno

## Arranque de la aplicacion

Arrancar mongodb server

```
mongod
```

En carpeta backend

```
npm start
```

En carpeta de frontend

```
npm start
```

INFO

- Cada vez que se cree un nuevo usuario, se enviara un correo de verificacion del correo "whataduck.project@gmail.com"
- Cada vez que se inicia sesión se guardan 3 Cookies. (El primero guarda el token de Sesion, el segundo guarda el nombre del Usuario que inicio sesion, la tercera Cookie guarda el correo de el Usuario que inicio sesión
- El buscador de publicacion funciona con los nombres de los productos
- Si ocurre un error en el envio de Correo, es posible que sea porque se intenta enviar desde otro país diferente al país de origen que fue creado el Correo (Ecuador).
- La Base de datos se llama wallapop, con 2 colecciones de "adverts" y de "users", en el caso de que no se cree automaticamente, se puede crear manualmente
