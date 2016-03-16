# NewsFeed - Grability test app

NewsFeed es una aplicación web sencilla basada en web components, que obtiene una serie de "noticias" a partir de una llamada a una url la cual devuelve un objeto JSON y es presentado en una interfaz amigable para el usuario.

NewsFeed fue desarrollado con la velocidad en mente y la idea de poder precargar el contenido generando un caché inicial, de tal forma que el usuario no perciba la etapa de carga de información y su experiencia sea lo mas fluida posible.  Para las animaciones se crearon custom elements que extienden la funcionalidad de la libreria neon-animations de Google.

## Consideraciones

La aplicacion tiene integrado un input en el cual se encuentra preestablecida una ruta con un archivo JSON, sin embargo el texto del  input puede y debe ser cambiado por otra url que apunte a un API cuya respuesta sea un archivo JSON con la misma estructura del de prueba, en caso de no encontrarlo, la aplicacion dispone de un mensaje de alerta ante posibles errores 404.

## Versión
0.0.1

## Recursos

* Google Polymer - Web components
* Bower - Gestor de Paquetes
* GIT - Control de versiones


## Instalación

Instalar newsFeed no puede ser mas facil, simplemente debemos clonar el repositorio a nuestra carpeta de producción, ya sea que usemos XAMPP o tengamos nuestro propio servidor local APACHE.

#### 1. Navegamos hasta nuestra carpeta (ejemplo con XAMPP)
```sh
$ cd /Applications/XAMPP/xamppfiles/htdocs
```
#### 2. Clonamos el repositorio y estamos listos para probarlo
```sh
$ git clone https://github.com/dramirezc90/newsFeed.git
```
#### 3. Opcionalmente se recomienda configurar bower en caso de desear instalar mas paquetes.
```sh
$ npm install -g bower
$ bower install <package>
```
