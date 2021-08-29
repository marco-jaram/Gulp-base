# PROYECTO DE INICIO GULP
Con este proyecto podras iniciar para procesar css y javascript,

# Instalar
Con las carpetas y las configuraciones necesarias para compilar
Al clonar este paquete solo descomprime y desde la terminar y dentro de la carpeta utilizar
$ npm install
Con ello se intalara node modules (necesario) y todo lo que esta en el .JSON (dependencias).

# Correr gulp
Una vez instalado todo. Ahora desde la carpeta de nuestro proyecto y desde la termianl escribir $ gulp
Enseguida correra automaticamente:
 * scssTask, compila los estilos de sass y los envia carpeta dist
 * jsTask, compila javscript y los envia a carpeta dist
 * browsersyncServe, abre navegador con nuestro proyecto
 * watchTask, crea un actualizador en tiempo real.
   Solo dos tareas no se realizan en automatico: Optimizacion de imagnes y minimizacion de codigo. Para ejecutar estas tareas hay que escribir desde terminal:
   * $ gulp imagenes
   * $ gulp nanoTask


# Estructura de proyecto
Todo el proyecto de edicion de Sass esta en la capeta App con los siguientes archivos sass:
* base (extens, globales, mixins, normalize, variables)
* layout (headers footers, iglinks, menus)
* paginas (1home, 2acercade,3servicios, 4contacto, 5aviso-privasidad)
  Importadas a una solo archivo llamado styles.scss de sass

TODAS las capetas de App se compila en la carpeta dist en las siguientes sub carpetas
* css
* img
* js


