# NewsFeed Aplication

NewsFeed es una aplicación web sencilla basada en web components, que obtiene una serie de "noticias" a partir de una llamada a una url la cual devuelve un objeto JSON y es presentado en una interfaz amigable para el usuario.

NewsFeed fue desarrollado con la velocidad en mente y la idea de poder precargar el contenido generando un caché inicial, de tal forma que el usuario no perciba la etapa de carga de información y su experiencia sea lo mas fluida posible.  Para las animaciones se crearon custom elements que extienden la funcionalidad de la libreria neon-animations de Google.


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
