Este es el seguimiento de un tutorial de [Clear Code](https://www.youtube.com/watch?v=QU1pPzEGrqw&t=48s) en el cual usaremos Pygame para el desarrollo de un juego al estilo de zelda

# Configuracion del proyecto

Como se recomienda el "corazon" del proyecto esta en nuestro archivo [main]('code/main')

importaremos [settings]('code/settings.py') que es donde estaran las configuraciones de nuestro proyecto.


### Main.py
Comenzamos con una inicializacion basica de pygame dentro de nuestra classe **Game** asignando una pantalla con los tamanios definidos en _settings_ y un reloj para controlar el flujo de imagenes.

En el metodo run de nuestra clase establecemos la condicion de cierre dentro de un for que estara esperando el evento _QUIT_. para luego hacer un llenado de la pantalla con un color negro terminando con la actualizacion de la pantalla(o redibujado) y estableciendo la velocidad del juego o de frame con FPS.

Todo esto solo se iniciara si **main** esta siendo llamado como principal.
