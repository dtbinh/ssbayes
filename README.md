# ssbayes
Implementación y evaluación de un entorno experimental para localización de robots móviles usando filtros de Kalman.
==========
Trabajo realizado por Iván Rodríguez Méndez bajo la dirección de Leopoldo Acosta Sánchez y Antonio Luis Morell González. 

Universidad de la Laguna.

Junio de 2016

Vídeo demostrativo del funcionamiento del entorno experimental:
[http://youtu.be/oKTTHTu33Vo](http://youtu.be/oKTTHTu33Vo)

Resumen
--------------------

Uno de los problemas que más esfuerzos en investigación han generado en el ámbito de la robótica móvil, es sin duda la estimación de estados, aplicada en concreto a la localización.
En este proyecto se pretenden estudiar una serie de herramientas con una sólida base estadística, llamadas filtros Bayesianos.
Dentro de este tipo de filtros se estudiarán lo que se conocen como filtros de Kalman.
En concreto estudiaremos cuatro tipos de filtros de Kalman, formulados para aplicarse a diferentes situaciones.
Los filtros que estudiaremos a lo largo del trabajo serán: el filtro de Kalman clásico, el filtro de Kalman extendido, el filtro de Kalman unscented y el filtro de Kalman de Cubatura.
Además, estudiaremos la implementación de estos en MATLAB para comprobar cual es el que presenta una mejor estimación para la localización de un robot móvil.
Para determinar cual es el mejor de los filtros diseñaremos una serie de experimentos que nos ayudarán a detectar los puntos débiles y el que presente un mejor funcionamiento.
Para la implementación de los experimentos utilizaremos V-REP, un programa que nos permite simular dinámicas reales para múltiples robots, sensores, actuadores e interacciones con diferentes entornos.
Finalmente, con ayuda de esta herramienta obtendremos conclusiones sobre cuál es el filtro que presenta un mejor rendimiento, los puntos débiles, y evaluaremos si esto guarda relación con lo estudiado en los capítulos en los que hemos realizado la explicación teórica de cada uno.

Funcionamiento del entorno experimental
--------------------

Cooming soon
